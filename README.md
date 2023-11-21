# 나의 첫 프로젝트
- Repository 정보등록
- 원격 Repository 생성
- 로컬 폴더(test1) 에 README.md 파일 생성
- 로컬 Repository 생성
- 로컬 폴더 압축하여 로컬 Repository 에 저장
- 원격 Repository 에 push 하기

## Repository 정보 등록
- 컴퓨터 포멧했을때 최초 한번만
- username 등록 : **git config --global user.name WHM0304**
- email 등록 : **git config --global user.email whm0304@naver.com**

## 로컬 Repository 생성하기
- **bash shell** 에서 **git init** 
명령실행하기: **.git** 폴더가 생성된다

## 원격 Repository 와 
로컬 Repository 연결하기 :git remote add origin https://github.com/WHM0304/Biz-2024-11-First.git


## 원격 Repository 에 push 하기
- 로컬 폴더의 파일, 폴더들을 로컬 Repository에 압축하여 저장하기 : **git add README.md**
- 왜 push 를 하는지 comment 부착하기 : **git commit -m "커멘트"**
- push 하기