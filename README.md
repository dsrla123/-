## TIL 

## Remote Repository 연결하기

### Remote Repo 생성하기

1. 기본 브랜치 이름 master로 변경하기
2. new Repo 생성 버튼 눌러서
   1. 이름 설정
   2. 만들기

### Local

1. git remote add origin (원격 레포 주소url)
2. 

1. 새로운 디렉토리 생성:

   

   1. mkdir
   2. cd(경로)
   3. git init
   4. git remote add origin (원격 레포 주소url)
   5. git remote: origin 이름으로 remote 추가된 것 확인
   6. touch README.md

2. 버전 남기기(remote repo로 push하기 전에 반드시 commit이 있어야 한다)

   1. git add( 파일명.확장자)
      1. git.add . (현재 위치 wd 모든 변경사항 추가)
   2. git commit -m 'first commit'

3. git push origin master

