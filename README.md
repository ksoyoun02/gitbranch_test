# 브랜치 생성방법
git checkout main
git checkout -b develop
git push origin develop

git checkout develop
git checkout -b feature/로그인기능

# 브랜치 제거방법
1. 현재 브랜치 목록 확인
git branch -a

2. 로컬에서 삭제
git branch -d staging   # 예시: staging 브랜치 삭제

3. 원격에서도 삭제
git push origin --delete staging
