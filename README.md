# git
# 1. git을 사용하는 이유
: 프로젝트를 진행할 때 A-Z까지 혼자 모든 일을 할 수는 없다.<br>
여러 사람이 협업해서 프로젝트를 진행하게되는데 버전, 코드 공유 등 여러 가지 코딩 외 <br>
실무적인 문제 발생<br>
: 이러한 실무적인 문제를 해결해주는 것이 github<br>
: 포트폴리오도 올릴 장소가 필요<br>
(내 소스코드를 저장 (버전관리))<br>
(소스코드 공유)<br>
(협업하는 공간)<br>

# 2. github download(https://github.com/)
- sign up<br>
- sign in<br>

# 3. new button click
- Repository name <br>
프로젝트 이름<br>
- public / pricate<br>
전체공개 혹은 비공개<br>
전체공개 모드여야 코드를 남들이 볼 수 있음<br>
create repository<br>
(github는 소스코드를 올리는 어떤 공간)<br>
(소스코드를 내 컴퓨터에서 github에 올려주는 역할이 git)<br>
# 4. git download (https://git-scm.com/downloads)

# 5. git bash open
- Step 1 : username to using for git commit<br>
git config --global user.name "your_name"<br>
- Step 2 : email to use for git commit<br>
git config --global user.email "your_email"<br>
- Step 3 : git config --list<br>
알 수 없는 어려운 말들이 나오지만 user.email, user.name 부분만 정상적으로 되었는지 확인<br>
config end<br>

# 6. git push

visual studio code terminal click<br>
git init -> 초기화(!!맨처음!! 프로젝트를 올릴 때)<br>

git add . -> .은 전부라는 의미 <br>
git add gitTest.c -> 선택해서 add하는 경우<br>

git status (보여주기용)<br>

git commit -m "history name"<br>
수정사항 -> 마지막수정사항 -> 진짜마지막수정사항<br>

history를 github에 보내야 하는데 연결고리가 없음<br>
git remote add origin git@github.com:dotdotot/git.git<br>
git remote -v<br>

git push origin main<br>

# 7. code update
git init은 필요하지 않다.<br>
(처음에 한번 했기에 추가하는 작업은 필요없다.) <br>
git add .<br>
git status<br>
git commit -m "second gitTest commit"<br>
git push origin main<br>

gitgub 새로고침<br>

# 8.
# 9.
# 10.