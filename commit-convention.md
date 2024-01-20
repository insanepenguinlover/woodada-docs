```javascript
[prefix] #이슈번호 subject

ex)[Feat] #2 vercel 배포


* Merge의 경우 [Merge] 병합 주체 브랜치 <- 병합될 브랜치

ex) feature/2 브랜치에서 dev 브랜치로 머지 커밋을 작성하는 경우
[Merge] dev <- feature/2
```
## prefix
- `Feat` : 기능 추가/수정/삭제
- `Fix` : 버그 수정
- `Docs` : 문서 수정
- `Style` : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
- `Refactor` : 코드 리팩토링
- `Chore` : 패키지/빌드 관련 수정
- `Env` : 개발 환경 관련 설정
- `Design` : CSS등 디자인 추가/수정
- `Rename` : 파일 및 폴더명 수정
- `Remove` : 파일 삭제
- `Merge` : PR 머지
  
## subject
- 마침표 및 특수기호를 사용하지 않습니다.
- 가능한 한글로 작성합니다.
