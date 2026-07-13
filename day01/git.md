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

