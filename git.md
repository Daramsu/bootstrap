git (털) 의 
1. 코드를 쉽게 공유할 수 있다. (압축파일을 주는 대신 '레퍼지토리'를 준다)
2. 버전컨트롤
bootstrap.zip
bootstrap(1).zip
bootstrap_2021-7-1.zip
bootstrap_2021-7-3.zip
bootstrap_2021-7-19.zip
3. 날아가지 않게 저장


github란, git이 아니다.
git repository를 웹상으로 공유할 수 있게 해주는
웹서비스다.


git 사용 방법

0. 상식 cli, gui 
gui - graphic user interface
cli - command line interface
    ctrl + ` (1왼쪽) : vscode에서 터미널 열기
	ls : 현재 위치에 있는 디렉토리, 폴더의 목록 보여주기 (list)
	cd [디렉토리명]: (ex, cd 다람) [디렉토리명] 디렉토리로 이동. (change directory)
        cd ..  : 이전 디렉토리로 돌아가자.
        cd ~ : 현재 유저의 홈 디렉토리로 돌아가자.
             ~ 은 홈. c://user/hwayo, 현재 유저의 디렉토리
	mkdir : (make directory)
	rm : (remove) / 디렉토리 지우려면 rm -rf [디렉토리명]

    # 숨김폴더 # 
    폴더이름 맨 앞에 . 이 붙어있으면 숨김폴더이다.
    그냥 ls 하면 보이지않음
    ls -al : 숨김폴더까지 해서 보여줘

1. git 기본명령어
git init : 지금 디렉토리를 git repository로 만든다.
git clone [주소] : '주소' 로 '외부의' git repository를 받아온다.
git status : git 의 상태를 알려준다.
    추적/스테이징/커밋. git 레퍼지토리 안에 있는 파일들은 이 세가지 상태중에 하나야. 
    추적 : 깃이 관리를 해준는 파일이라는 뜻
    스테이징 : 커밋을 하기 전에 임시 저장상태
    커밋 : 하나의 버전으로써 스테이징 상태에 있는 파일들을 찰칵 저장.
git log : git 에 저장된 버전들을 보여준다.
git add [-A / 파일이름]: 스테이징 상태로만든다
git commit -m '커밋메시지' : 스테이징 되어있는 변화들을 찰칵. 저장해서 하나의 버전으로 저장.
git push : 외부 저장소에, 로컬 저장소(repository)에 있는 커밋들을 밀어넣음
git pull : 외부저장소에 있는 커밋들을 로컬저장소에 받아옴.
(push를 하기 전엔 pull 을 무조건 해야햄.)



github 로그인 토큰
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