1.
git의 명령어 add, commit, push는 각각 어떤 역할을 하는지 정리하고,
git pull과 fetch의 차이점을 정리하시오. 

 git의 add 명령어는 다음 변경(commit)을 기록할 때까지 변경분을 모아두기 위해 사용한다. 따라서 commit명령어를 통해 명시적으로 기록을 남기기 전까지 git 저장소의 변경 이력에는 어떤 영향도 주지 않는다.
 commit 명령어는 staging area의 모든 파일을 commit하며 저장소에는 하나의 스냅샷으로 기록된다.
 push 명령어는 local repository 에서 remote repository로 코드 변경분을 업로드 하기 위해 사용한다.

 git pull과 fetch의 차이점은 fetch는 local git에게 remote repository에서 최신 메타데이터 정보를 확인하라는 명령을 전달한다. 하지만 fetch는 remote repository에 변경사항이 있는지만 확인만 하고, 변경된 데이터를 local git에 실제로 가져오지 않는다. 반면 pull은 remote repository에서 변경된 메타데이터 정보를 확인한뿐만 아니라 최신 데이터를 복사하여 local git에 가져온다. 

2.
지난 주와 이번주 학습 내용을 정리하고 WIL을 작성하여 제출한다.

1주차
리소스는 컴퓨터 시스템에 관한 여러 가지의 자원을 총칭하는 말로 어딘가에 저장되어 있으며 이것을 찾으러 가는 길이 URI다.
URI는 리소스를 찾는방법으로 인터넷에 있는 자원을 나타내는 유일한 주소이며 그안에 URN과 URL이 있다. 
URN은 이름으로 찾는 것이며, 영구적이 소장 위치에 관계 없이 정보자원을 식별하는 고유 기호로이다.
URL은 웹페이지에서 주관하는 자원에 접근할 수 있는 모든 데이터로, 정보가 들어있는 위치를 나타내는 주소다.
서버라는 가상의 컴퓨터가 있고 그 안에 데이터가 저장되어 있으며 URL로 그 위치를 특정해서 자료를 받아올 수 있다. 
이때 사람은 긴 숫자를 외우는데 취약하여 숫자 형태의 IP 주소를 기억하기 쉽게 대신 이름을 붙여주고 그 이름들을 관리하는 서버가 DNS다.

리소스 파일들은 html,css,js을 이용해서 브라우저의 화면들을 꾸며준다.

2주차
GIT은 파일의 변경할 수 있으며 사람들간의 작업을 조율할 수 있다. 
깃은 코드의 수많은 다른 버전을 만들 수 있다. 그 분기들을 브렌치라 부른다.
분기들을 나눌 수 있으며 합칠 수도 있고 특정 지점으로 돌아가거나 변화를 추적(버전 관리)할 수 있다. 
파일에는 4가지 종류가 있으며 이 4가지 상태로 파일들을 관리한다. (추적x(untracked), 변경x(unmodified), 변경o(modified), staged) 이 4가지 상태로 파일들을 관리한다.

working directory, staging area, local repository는 내 컴퓨터 안에서 일어나는 일이다.
working directory는 내가 작업하는 공간으로 코드 작성할 때 보이는 공간이다.
staging area는 commit하기 전에 잠깐 내용(변화)들을 쌓아두는 곳이다.
local repository는 GIT에서 관리하는 어떤 저장소이다.
변화를 추가하고 싶으면 add라는 명령어를 이용하여 staging area로 넘길 수 있고 내용물이 쌓이면 commit으로 보낼 수 있으며 이를 local repository에 저장할 수 있다. 
staging area가 있는 이유는 논리적으로 끊어주기 위해서이다. (각각 뭘 한건지 구별할 수 있도록) commit을 할 때 이름을 붙여준다.
remote repository는 중앙에서 코드를 공유할 수 있도록 관리해주는 시스템으로 GIT HUB가 있다.
push라는 명령어를 통해 내 변경사항을 remote repository로 보낼 수 있다. 
fetch는 내 working directory에 반영되지 않지만 변경사항을 만들었는지 확인한다.
pull은 내 working directory에 반영되지 않은 변경 사항을 합칠 때 이용한다. 
clone은 remote repository에 있는 내용을 복사하는 것이다.
