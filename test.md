[오늘 수업 주제7] Remote Repository

# Remote Repository

## 원격 저장소
: 코드와 버전 관리 이력을 온라인 상의 특정 위치에 저장하여 여러 개발자가 협업하고 코드를 공유할 수 있는 저장 공간

> 다양한 원격 저장소 서비스

1. GitLab	2.  GitHub	 3. Bitbucket

# 로컬 & 원격 저장소

## remote

> 로컬 & 원격 저장소

1. GitHub 가입
2. 공용 문서 "GitHub 설정 변경하기" 문서 진행
3. GitHub repository 생성

> GitHub 설정 변경하기
	1. github 접속 후 로그인
	2. `프로필 버튼` -> `Settings` -> `Repositories`를 클릭하고, main을 `master`로 수정한 후 `Update`를 클릭한다.


### `**git remote** add origin remote_repo_url

-> git remote : 로컬 저장소에 원격 저장소 추가
-> origin : 추가하는 원격 저장소 별칭 - 별칭을 사용해 로컬 저장소 한 개에 여러 원격 저장소를 추가할 수 있음
-> remote_repo_url : remote repo의 위치 (URL), 추가하는 원격 저장소의 주소
-> github에서 repo 새로 만들고 repo name만 입력하고 create repo하기!
-> 주소 카피 후 `git remote add origin ` 뒤에 붙여넣기

- git remote -v 로 등록된 원격 저장소 목록 확인


# push

: Local Repository -> GitHub Repository로 보냄

## `**git push**` origin master

: 원격 저장소에 commit 목록을 업로드

-> git push : "git아, push 해줘 origin 이라는 이름의 원격 저장소에 master라는 이름의 브랜치를"

> git push