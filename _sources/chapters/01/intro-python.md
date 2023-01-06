## 파이썬 환경구성
<!-- 1-1 -->

### Anaconda의 설치

Anaconda는 머신러닝이나 데이터 분석 등에 사용하는 여러가지 패키지가 기본적으로 포함되어있는 파이썬 배포판입니다. 여러가지 파이썬에서 사용할 수 있는 패키지들을 설치할 때 패키지간 의존성을 관리 해주며, 가상환경을 만들어 패키지들을 해당 가상환경에서만 사용할 수 있도록 제한해줍니다. 

Anaconda를 사용하면 패키지간 충돌을 줄일 수 있으며, 충돌이 난 패키지가 있을 경우에 가상환경만 새로 설치하면 되기 때문에 전체 시스템을 수정해야하는 수고를 덜 수 있습니다. 잘 사용하고 있던 개발환경이 새로운 패키지를 설치한 후 작동하지 않는 상황을 상상해보십시오. 

1. Anaconda의 설치 방법 (window)
    - Anaconda 다운로드 사이트 (https://www.anaconda.com/)
        운영체제에 맞는 파일을 다운로드 받고 설치한다. 
        
        ![](./image/install.png)
    <center>    (아나콘다설치화면) </center>
   
    - Anaconda 설치 경로의 확인

        폴더의 경로창에 *%userprofile%\anaconda3*를 입력

        ![](./image/path.png)
        <center>    (설치경로) </center>
    
    - 환경변수를 설정
        (1) %userprofile% 의미
            %userprofile% 는 윈도우 상에 현재 로그인된 사용자의 바탕화면, 문서, 비디오등 개인화된 폴더의 위치를 반환한다. 예를 들어 윈도우에 로그인한 사용자의 이름이 *test* 인 경우 %userprofile%은 *c:\users\test* 의 위치를 의미한다.
        (2) path 설정 찾아가기
            - 내PC
            - 속성
            - 고급시스템설정
            - 환경변수
            - 사용자변수의 path 선택 후 편집 버튼 클릭
            - 새로만들기 클릭
        (3) 아래의 path 추가
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

1. vscode 설치하기
    (1) vscode 다운로드
        다운로드 사이트(https://code.visualstudio.com/) 

    (2) vscode의 실행 및 확장(extension)설치
        - python
        - code runner
        - remote –ssh

2. vscode를 통한 anaconda  파이썬 실행 
    (1) 가상환경의 선택 (shirf+ctrl+p → Python: select interpreter)
    (2) 쥬피터 단축키 설정 (ctrl+, → extension(설정) → jupyter → send selection to interactive window 에 체크
    (3) 새파일 만들기 (확장자 py로)
    (4) 계산기 코드 작성후 shirt+enter