# gitgit
git 자주쓰는 명령어 모음

## git fetch

`git fetch -p` : 원격 저장소에서 삭제된 branch 정리

`git checkout -q [파일경로]` : 파일의 변경사항 버림

`git checkout -q --track [origin branch name]` : branch 를 새로 생성하고 원격 branch 를 추적함

## git branch

`git branch --list` : local branch 목록 출력

`git branch --delete` : local branch 삭제

## git stash

`git stash` : commit 되지 않은 변경사항을 stash 에 저장함

`git stash apply` : stash 에 저장된 변경사항을 현재 branch 에 적용함

`git stash list` : 저장된 stash 보기

`git stash drop` : 가장 최근 stash 삭제

`git stash drop` [stash 이름] : stash 삭제


## git remote

`git remote -v` : 원격 저장소 url 보기

## git clean

`git clean` : 추적되고 있지 않은 모든 파일을 삭제함

`git clean -n` : git clone 명령으로 삭제될 파일을 보여줌


## git revert


`git revert [commit]` : 대상 commit 전 상태로 코드를 되돌리고 새로운 commit 을 생성함


## git reset

`git reset [commit]` : 대상 commit 상태로 코드를 되돌림

`git reset --hard [commit]` : 대상 commit 상태로 코드를 되돌리고 commit 을 삭제함

