# devops_assistant

프로젝트 진행 상황을 한눈에 관리하고 KPI 지표를 확인할 수 있는 웹 대시보드를 기획하는 저장소입니다.

## 현재 산출물

- [CRS.md](/home/yklee/repos/devops_assistant/docs/requirements/CRS.md): KPI 12개, 테스트 7종, 품질 4종의 탭 배치 요구를 포함한 고객 요구사항 문서
- [SRS.md](/home/yklee/repos/devops_assistant/docs/requirements/SRS.md): KPI 12개, 테스트 7종, 품질 4종의 탭별 표시 구조와 메인 대시보드, 프로젝트 목록/상세, 상단 검색, 시계열/조직 필터, 개인 할 일, 경고/알림 요구를 분석한 소프트웨어 요구사항 문서
- [main_dashboard_sketch.svg](/home/yklee/repos/devops_assistant/samples/main_dashboard_sketch.svg): 메인 페이지 UI 스케치
- [version.md](/home/yklee/repos/devops_assistant/version.md): 현재 개발 버전 정보

## 요구사항 요약

- 메인 페이지에서 전체 프로젝트 요약을 제공한다.
- 프로젝트별 현황 탭에 KPI 12개 항목을 표시한다.
- 프로젝트별 현황, 테스트 현황, 소스코드 품질 현황을 탭으로 전환해 확인할 수 있다.
- 테스트 현황 탭에는 테스트 관련 지표 7종을 표시한다.
- 소스코드 품질 탭에는 품질 관련 지표 4종을 표시한다.
- 상단 네비게이션 바에서 메뉴 이동과 프로젝트 검색을 지원한다.
- 프로젝트 목록 화면과 프로젝트별 상세 페이지를 제공한다.
- 조회 범위 필터는 `시계열(년도, 월)`과 `조직(팀, 그룹, 파트)`으로 분리한다.
- 접속한 사용자의 할 일 요약을 별도 영역에 표시한다.
- 진행 지연, 테스트 실패, 품질 저하 등 경고와 알림을 메인 페이지에서 빠르게 식별할 수 있게 한다.
- KPI 12개 항목, 테스트 7종, 소스코드 품질 4종의 상세 정의는 이후 단계에서 구체화한다.
