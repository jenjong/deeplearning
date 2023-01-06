## 파이썬 환경구성
<!-- 1-1 -->

### Anaconda의 설치

    아나콘다는 머신러닝이나 데이터 분석 등에 사용하는 여러가지 패키지가 기본적으로 포함되어있는 파이썬 배포판.
    여러가지 패키지들을 설치할 때

1. Anaconda의 설치 방법 (window)

    - Anaconda 다운로드 사이트 (https://www.anaconda.com/):
        운영체제에 맞는 파일을 다운로드 받고 설치한다. 

        <figure>
            <img src="./image/install.png" title="하얀 강아지">    
        <figcaption>하얀 강아지</figcaption>
        </figure>

        
<br/><br/>
    - Anaconda 설치 경로의 확인
        폴더의 경로창에 '%userprofile%\anaconda3'를 입력

        ![설치경로확인](./image/path.png)
    

    - 환경변수를 설정:

        (1) %userprofile% 의미
            %userprofile% 는 윈도우 상에 현재 로그인된 사용자의 바탕화면, 문서, 비디오등 개인화된 폴더의 위치를 반환한다. 예를 들어 윈도우에 로그인한 사용자의 이름이 'test'인 경우 %userprofile%은 'c:\users\test' 의 위치를 의미한다.

        (2) path 설정 찾아가기


        (3) path
            - %userprofile%\anaconda3
            - %userprofile%\anaconda3\library
            - %userprofile%\anaconda3\scripts


2. Anaconda의 설치 방법 (Mac)
    - Anaconda 다운로드 사이트 (https://www.anaconda.com/)
        운영체제에 맞는 파일을 다운로드 받고 설치한다. 
    - 특별한 설정 필요 없음


    

### 가상환경과 파이썬의 실행

1. anaconda의 실행
    (1) anaconda 실행하기
        - 윈도우
            왼쪽 아래 실행창에 anaconda로 검색후 anaconda prompt (anaconda3)를 클릭



        - 맥

    (2) python 실행하기 및 python 버전 확인하기
    (3) python에서 계산기 기능 이용해보기
    (4) python 종료하기: exit()

2. python 위에서 명령과 shell 명령의 구분 
(1) shell 위에서 계산 시도해보기
(2) dir (window) 명령, ls (mac) 명령
(3) cd 명령과 파일경로의 이해

3. 가상환경의 설치와 삭제
(1) conda create –n test python=3.8
(2) conda info 
(3) conda activate, 파이썬 실행 및 버전확인, conda deactivate
(4) 가상환경내 ipykernel의 설치
(5) conda remove env –n test


### vscode를 이용한 파이썬 실행

vscode 설치하기
(1) vscode 다운로드

그림  	다운로드 사이트(https://code.visualstudio.com/)

(2) vscode의 실행 및 확장(extension)설치
- python
- code runner
- remote –ssh

2. vscode를 통한 anaconda  파이썬 실행 
(1) 가상환경의 선택 (shirf+ctrl+p → Python: select interpreter)
(2) 쥬피터 단축키 설정 (ctrl+, → extension(설정) → jupyter → send selection to interactive window 에 체크
(3) 새파일 만들기 (확장자 py로)
(4) 계산기 코드 작성후 shirt+enter