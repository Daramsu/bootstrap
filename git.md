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
git status : git 의 상태를 알려준다.
git log : git 에 저장된 버전들을 보여준다.
git add
git commit
git push
git pull

