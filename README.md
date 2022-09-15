# git
===============
# 1. git을 사용하는 이유
---------------
#### : 프로젝트를 진행할 때 A-Z까지 혼자 모든 일을 할 수는 없다.<br>
#### 여러 사람이 협업해서 프로젝트를 진행하게되는데 버전, 코드 공유 등 여러 가지 코딩 외 <br>
#### 실무적인 문제 발생<br>
#### : 이러한 실무적인 문제를 해결해주는 것이 github<br>
#### : 포트폴리오도 올릴 장소가 필요<br>
##### (내 소스코드를 저장 (버전관리))<br>
##### (소스코드 공유)<br>
##### (협업하는 공간)<br>

# 2. github download(https://github.com/)
---------------
#### - sign up<br>
#### - sign in<br>

# 3. new button click
---------------
<img src="https://user-images.githubusercontent.com/77331459/190469729-6854ea9c-1159-417d-84b0-c1dc713c41de.png" width="100%" height="100%">
<!-- ![KakaoTalk_20220915_225616387](https://user-images.githubusercontent.com/77331459/190469729-6854ea9c-1159-417d-84b0-c1dc713c41de.png)<br> -->
#### 프로젝트 이름<br>
####    - public / pricate<br>
#### 전체공개 혹은 비공개<br>
#### 전체공개 모드여야 코드를 남들이 볼 수 있음<br>
####    create repository<br>
![KakaoTalk_20220915_225632855](https://user-images.githubusercontent.com/77331459/190469732-148a4b97-ac82-4fb2-8614-f771ff59e270.png)<br>
![KakaoTalk_20220915_225825808](https://user-images.githubusercontent.com/77331459/190469735-496be76e-1c17-4817-9a56-f851710ac9bb.png)<br>
##### (github는 소스코드를 올리는 어떤 공간)<br>
##### (소스코드를 내 컴퓨터에서 github에 올려주는 역할이 git)<br>
# 4. git download 
---------------
(https://git-scm.com/downloads)<br>

#### all next
# 5. git bash open
---------------
![KakaoTalk_20220915_230108546](https://user-images.githubusercontent.com/77331459/190469737-59fec3b5-10c2-4970-a0c0-c047aa452732.png)<br>
#### - Step 1 : username to using for git commit<br>
####    git config --global user.name "your_name"<br>
#### - Step 2 : email to use for git commit<br>
####    git config --global user.email "your_email"<br>
![KakaoTalk_20220915_230232564](https://user-images.githubusercontent.com/77331459/190469738-387c7a92-f777-4a4e-8b82-d7810eed191a.png)<br>
#### - Step 3 : git config --list<br>
![KakaoTalk_20220915_230313148](https://user-images.githubusercontent.com/77331459/190469739-55880305-235a-4434-8d44-f4d4508fd50e.png)<br>
####    알 수 없는 어려운 말들이 나오지만 user.email, user.name 부분만 정상적으로 되었는지 확인<br>
#### config end<br>

# 6. git push
---------------

#### visual studio code terminal click<br>
####    git init -> 초기화(!!맨처음!! 프로젝트를 올릴 때)<br>
![KakaoTalk_20220915_231529633](https://user-images.githubusercontent.com/77331459/190469702-7dc25193-b05d-4dbb-903b-51d9ae2e5c0b.png)<br>
####    git add . -> .은 전부라는 의미 <br>
####    git add gitTest.c -> 선택해서 add하는 경우<br>

####    git status (보여주기용)<br>
![KakaoTalk_20220915_231724772](https://user-images.githubusercontent.com/77331459/190469705-4188edcf-a1c9-4a79-9e13-54caf580629a.png)<br>
####    git commit -m "history name"<br>
#### 수정사항 -> 마지막수정사항 -> 진짜마지막수정사항<br>
![KakaoTalk_20220915_231845466](https://user-images.githubusercontent.com/77331459/190469707-801dff26-a292-42b7-b01e-bca58c5260db.png)<br>
#### history를 github에 보내야 하는데 연결고리가 없음<br>
####    git remote add origin git@github.com:dotdotot/git.git<br>
####    git remote -v<br>
![KakaoTalk_20220915_232007016](https://user-images.githubusercontent.com/77331459/190469710-bea587ce-3c05-4431-8a55-8b766cb935fd.png)<br>

####    git push origin main<br>
![KakaoTalk_20220915_232030908](https://user-images.githubusercontent.com/77331459/190469713-eee12472-0e10-4f27-8be3-3189997ffe0e.png)
# 7. code update
![KakaoTalk_20220915_234011337](https://user-images.githubusercontent.com/77331459/190469719-a876ac06-ef6a-428c-ae10-d54858d72ef2.png)
---------------
#### git init은 필요하지 않다.<br>
#### (처음에 한번 했기에 추가하는 작업은 필요없다.) <br>
####    git add .<br>
####    git status<br>
####    git commit -m "second gitTest commit"<br>
####    git push origin main<br>

#### gitgub 새로고침<br>

# 8. git pull
---------------
#### !!(권한주는거 잊어먹지말기)!!
#### 회사에 신입이 들어와서 회사에서 기존에 사용하고있던 코드를 모두 pull해야 합니다.
#### 회사에서 배포한 github 주소로 접속해서 git주소를 복사
![KakaoTalk_20220916_000758257](https://user-images.githubusercontent.com/77331459/190469723-1e00355e-8329-4244-a8cd-d7ed054610b6.png)<br>

####    git clone https://github.com/dotdotot/git.git
####    git clone https://github.com/dotdotot/git.git freshmen
#### freshman 폴더 이름을 써주지 않으면 자동으로 프로젝트 이름의 폴더로 들어간다.

#### github에 들어있는 파일들이 모두 옮겨진 모습
![KakaoTalk_20220916_023033482](https://user-images.githubusercontent.com/77331459/190471827-9a85e5a1-6f95-41a1-9d44-736cc23815e0.png)<br>

#### 상사가 신입에게 어떠한 작업을 요구해서 작업을 진행
#### 작업을 완료했으면 기존 소스코드와 합쳐야한다.
####    git add .
####    git commit -m "freshmen commit"
#### !!git push origin main!!을 하면 정말 욕을 먹는다.
#### 왜냐 main에 있는 것들은 회사의 최종 결과물 신입이 무슨 권리로 본인이 작업한
#### 소스코드를 어떻게 올림?(에러가 엄청 많음)
![KakaoTalk_20220916_023033683](https://user-images.githubusercontent.com/77331459/190471834-0d9564b5-63f3-4ce1-be02-549d1a5e7f97.png)<br>


#### 신입사원은 메인이라는 최종 브렌치에 넣지 못하고 
#### 신입사원을 위한 새로운 공간을 만들어야한다.
####    git checkout -b freshmen
#### (main에서 freshmen으로 권한이 바뀐다)
#### 해당 공간을 아무리 망쳐도 최종 프로젝트에는 어떠한 영향도 미치지 않음

####    git push origin freshmen
![KakaoTalk_20220916_023033787](https://user-images.githubusercontent.com/77331459/190471836-857260a6-51fe-45d4-913b-be6326544b7e.png)<br>

#### 브런치가 새로 생긴걸 확인가능
![KakaoTalk_20220916_011150601](https://user-images.githubusercontent.com/77331459/190469727-0e85b0aa-c829-48b7-aa9d-d2551560f4c9.png)<br>

#### 신입 사원이 github 웹 사이트로 들어가보면 못보면 새로운게 발견
#### freshmen이라는 사람이 소스코드를 freshmen에 올렸다는 의미
![KakaoTalk_20220916_023033595](https://user-images.githubusercontent.com/77331459/190471833-2ada8482-c6fe-4350-8981-4c0886125e38.png)<br>

#### 그러면 full requests 공간에 freshmen이 수정한 내용이 올라옴.
#### 즉, 최종 프로젝트(main)에 해당 내용을 반영시킬 수 있게 허락해달라는 의미
#### 상사가 소스코드를 보고 마음에 안들면 review changes를 요청해서 반려시킬 수 있다.
#### 괜찮다면 merge pull request를 눌러서 최종 프로젝트(main)에 반영시킬 수 있다.
#### 최종 프로젝트에 합쳐짐.

#### 근데 상사도 본인이 개발을 하고있던 와중 신입이 만든 수정사항이 올라오고 최종 프로젝트에 합치면서
#### main 코드가 새걸로 바뀌었다.
#### main과 상사가 작성하던 소스코드랑은 완전히 버전이 다름
#### 이 상태에서 상사가 계속 소스코드를 개발을 하게되면 둘 사이에 버전이 완전히 달라지는일이 발생하기 때문에.
#### 최종 프로젝트에 무언가 반영이 된 후에는 모든 개발자가 동기화 시키는 작업을 해줘야한다.

#### 동기화
##  git pull origin main

#### 이런식으로 동기화를 진행
#### 일이 이런식으로 진행이된다 모든 개발자들이 풀 푸쉬를 반복하게 되며
#### 이런식으로 회사는 일을 하게되고 소스코드도 공유할 수 있고 협업도 할 수 있고
#### 개발자로써 리모트 잡이 가능하게 되는 것 


# 9. branch 권한
---------------
#### 신입이 실수로 main에 pull을 해버리는 경우가 발생하면
#### 최종 프로젝트는 그냥 날라가버리는 상황이 발생한다.

#### 그렇기에 git master branch에서 push를 하지 못하도록 설정할 수 있다.
#### github 설정에서 Branches에 들어간다음
#### Branch protection rules에서 add rules를 클릭
#### 여러 가지 설정이 있는데 가장 상단 require pull request before merging을 클릭하고 룰 추가 
#### 이렇게 하면 master branch로 push 했을 때 아래와 같이 error message가 나온다.
#### 애초에 Pull Request를 날리지 못하도록 차단!
#### 그리고 administrator (repository를 생성한 user)만 merge가 가능해진다.
#### PR 날리고 스스로 merge 하지 못하며 admin만 merge가 가능하므로, git 관리가 잘 이루어질 수 있다.

# 10.
---------------
