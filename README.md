# product_management_page

### Git-Flow 설정 및 브랜치 설정 이슈 설정
- master - develop - feature
- feature 브랜치에서 기능 개발 진행, 해당 issue 완성 시 develop에 merge
- 요구사항 하나 당 메인 issue 그 안에 Task 체크리스트로 만들어서 진행, 해당 요구 완료시 merge
- 해당 issue와 관련된 내용에 대해서 Commit message를 통해서 명확하게 구분해서 진행하기

### Commit Convention
- add : 개발한 기능에 대한 내용 및 정리
- modify : 패키지 개선 및 리팩토링
- fix : 관련 에러 해결
- docs : 문서화 작업

### 역할 구분
- folder 2개 각자 아이디 이름으로
- cloud0416, cheewr85
- 각자 작업물을 folder에 올려서 pr을 함 develop 브랜치로 PR 요청
- PR하고 commit & push 하기 전 사전에 미리 pull을 하여서 로컬 및 저장소는 항상 최신화 시키기