# git bash

1. 준비

```
Github.com 에 가입
git-scm.com 에서 다운로드 및 설치
git help -a 와 git config로 각종 명령어 확인
```

2. git bash 초기 세팅

``` 
git config --global user.name "닉네임"
git config --global user.email "abc@abc.com"
git config --global core.editor "vim"
git config --global core.pager "cat"
git config --global init.defaultbranch "main"
```

3. cmd 기본 명령어(git bash에서 사용)

```
help 로 각종 명령어 확인 가능
touch 파일명.확장자 = 파일 생성
ls = 현재 폴더에 있는 파일 확인
mv 파일명.확장자 폴더명 = 파일 옮기기
cd 디렉토리 변경
- cd ../ = 상위 폴더로 변경
- cd = 최상위 폴더로 변경
- cd 주소 = 주소 폴더로 변경
rm 파일명.확장자 = 파일 지우기
* = asterisk
예) rm **.md = md 파일 다 지우기
```

4. vim 기본 명령어

```
vi 파일명.확장자 사용하여 진입
Normal mode: 텍스트 편집 시 또는 ESC를 눌렀을 때
Input mode: Normal mode에서 a, i, o등을 눌렀을 때, 텍스트 입력 가능
Command mode: 저장 또는 나가기 등을 선택, 쉬프트+:으로 진입
 - :w 저장, :wq 저장 후 종료
 - :q! 저장하지 않고 강제종료
```

5. git 구조와 명령어(사용 순서 순)

```
 올리기
1. Working directory: 작성한 코드를 저장
 ↓+git add 파일명.확장자
2. Staging area: 작성 또는 변경상태가 저장
 ↓+git commit
3. Local repo: 변경한 건에 대한 commit을 달아 저장된 상태
 ↓+git push 
4. Remote repo: github로 업로드된 상태

 내리기
git fetch origin main + git merge FETCH_HEAD
또는 git pull origin main
git add 
git branch
git checkout
git clone
git commit
git config
git pull

```

6. 

