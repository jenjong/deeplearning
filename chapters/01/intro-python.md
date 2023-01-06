## 파이썬 환경구성
<!-- 1-1 -->

### Anaconda의 설치

1. Anaconda의 설치 방법

    Window

    Anaconda 다운로드 사이트 (https://www.anaconda.com/)



    Anaconda 설치 경로의 확인:

    환경변수를 설정:

    (1) %userprofile% 의미

    (2) path 설정 찾아가기

    (3) path
        - %userprofile%\anaconda3
        - %userprofile%\anaconda3\library
        - %userprofile%\anaconda3\scripts


    Mac: 특별한 설정 필요 없음


### 가상환경과 파이썬의 실행

anaconda의 실행
(1) anaconda 실행하기
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