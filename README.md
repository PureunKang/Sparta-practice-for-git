# Sparta-practice-for-git

# 커밋 메세지 남길 때, 레포지토리 페이지 - Wiki 카테고리 - [깃 커밋 컨벤션] 참고하여 남겨주세요!

# ex. git commit -m "feat : 프로젝트 세팅"

# 깃 특강 중 사용한 명령어 모음

1. 코드 복사하기
   git clone
   git pull

2. 코드 저장 및 업로드 명령어
   git add 파일명
   git commit -m "커밋 메세지 작성"
   git push

3. 저장 여부 확인하는 명령어
   git status

4. 저장 내역을 확인하는 명령어
   git log
   빠져 나올 때는, 키보드 q로 빠져나오기

5. 브랜치 생성 명령어
   git branch 브랜치이름

6. 브랜치 확인 명령어
   git branch

7. 브랜치 이동 명령어
   git switch 브랜치이름 (혹은, git checkout 브랜치이름)

8. 브랜치 생성 및 이동 명령어
   git switch -c 브랜치이름 (혹은, git checkout -b 브랜치이름)

9. 브랜치 합치는 명령어
   git switch 상위브랜치이름
   git merge 상위브랜치로 합쳐질 브랜치이름 \*깃헙 페이지 Pull Request 통해 합치기 가능

# 현재 필요한 브랜치

# 각 브랜치 하위 브랜치는 개인이 자유롭게 구성하여 연습하면 될 거 같습니다.

dev
ㄴfeature/header
ㄴfeature/footer
ㄴfeature/main
ㄴfeature/home
