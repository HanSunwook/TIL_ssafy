# Git
> 분산 버전 관리 시스템

1. Working Directory (CLI.md 기능, git.md 역할) 
2. Staging Area (기능에 포함시킬 것들만) commit->
3. Repository (버전을 만들어 Staging Area의 수정사항만)

> Git의 동작\ 
git init (git으로 관리)\
git status (git 변동사항 보기)\
git add CLI.md (CLI.md를 Staging Area에 추가)(-> git status 치면 바뀐거 보임)\
Staging Area 바뀐점은 숨김폴더에서 .git에 넣어져 있음
git commit (저장)

>git config --global user.email "~"
git config --global name "~"
code ~/.gitconfig (내 아이디 비번)

> git commit
insert or 'i' or 'a' 수정 가능
Esc 누르면 저장
:wq (저장하고 나가기)

commit해서 한 얘들은 로그에서 볼 수 있음


git status
git init 
git add 
git commit 
git log 

저장할 때 빨려들어가지 않기 위해 메세지만 간단하게
git commit -m "git.md 파일 추가 - git 추가 필기"
(")는 띄어쓰기 가능 문장이라는 표시임

한줄로 예쁘게 보기
git log --oneline

git log --oneline --graph

# 순서
git add day01/
status
git commit -m ""
status
git log


폴더에서 git 쓰지 않기

git remote add [설정이름] [주소]
관리하기

git remote -v
뭐 관리하고 있는지 확인할 수 있음

git push [설정이름] master
git에 push


파일 만들기
touch test.txt

git push -u [설정이름] master
앞으로 깃 푸시만 하면 됨.([] master 할 필요 없음)


# github
> gitignore 여기에 있는 파일은 전부 깃으로 관리가 안됨
> api key같은 것들 기록이 남으면 안되기 때문클 데이터, 세팅 등

내가 한번이라도 기록을 남긴 적이 있다면 원격 저장소에 뭔가를 추가로 해서 기록하게 된다면 같이 저장이 안되기 때문에
추가하면 안됨.

하지만 원격 저장소 먼저 만든다면 add README/.gitignore/license 등 추가해서 만들어도 가능.
