## 브랜치 구성
- `main`: 배포용 브랜치
- `develop`: feature 브랜치들을 merge하는 브랜치
- `feature/#이슈번호`: #이슈번호에 해당하는 기능을 개발하는 브랜치
- `feature` -> `develop` -> `main`

## 브랜치 관리 프로세스
1. 개발할 기능에 대한 이슈 작성
2. develop 브랜치를 기준으로 feature 브랜치 생성 및 checkout
3. 해당 feature 브랜치 내에서 개발
4. develop 브랜치로 push 후 PR 요청
5. 팀장이 코드 리뷰 후 approve
6. 자신이 develop 브랜치에 merge
7. 자신이 해당 브랜치 제거
