# 업무에 바로쓰는 HTML5/CSS3

## 환경구성
- 최신 웹브라우저 및 확장 프로그램 설치
  - visbug
  - tota11y
  - web develper
  - headingsmap
  - open wax
- Visual Studio Code  설치 및 확장 프로그램 설치
  - live-server
  - auto rename tag
  - auto close tag

- [node 설치](https://nodejs.org/ko/)
: LTS 버전
- [git 설치](https://git-scm.com/) : 최신버전

## Git 버전 관리
- [강사 저장소 Fork](https://github.com/seulbinim/webcafeHTML5)
- Fork한 저장소를 컴퓨터(Local)로 [Clone](https://github.com/hisslee/webcafeHTML5.git)  
```bash
git clone https://github.com/hisslee/webcafeHTML5.git
```

- 변경이력 및 상태확인  
```bash
git status
```
- Index Area 영역으로 이동
```bash
git add <파일명> || .
```
- 변경이력에 대한 확정본 생성
```bash
git commit -m "커밋메시지"
```
- remoter 저장소로 백업
```bash
git push origin main
```
- 변경 이력 조회(로그확인)
```bash
git log --oneline
```

## CLI 명령
- cd webcafeHTML5

##주요명령어(git)
git remote -v
git remote add lecture URL...
git add .
git add main.html
git commit -m "..."
git status
git log --oneline
git push origin main
