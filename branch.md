<img width="1399" alt="image" src="https://github.com/infruencer/woodada-docs/assets/46119135/6341c203-c6a7-4f1e-a762-94df0eacf5c3">

## 브랜치 구성
- `main`: 운영 서버 배포용 브랜치
- `dev`: 개발 서버 배포용 브랜치. feature 브랜치들을 merge하는 브랜치.
- `feature/이슈번호`: #이슈번호에 해당하는 기능을 개발하는 브랜치
- `feature` -> `dev` -> `main`

## 브랜치 관리 프로세스
1. 개발할 기능에 대한 이슈 작성
2. dev 브랜치를 기준으로 feature 브랜치 생성 및 checkout
3. 해당 feature 브랜치 내에서 개발
4. dev 브랜치로 push 후 PR 작성
5. 자신이 dev 브랜치에 merge(`Create a merge commint` 사용)
6. 자신이 해당 브랜치 제거
