# daily-paper-reports

음성 AI 분야(ASR, SpeechLLM, Speech Foundation Model)에 새로 나온 논문을 골라 읽기 쉽게 정리하는 리포트 저장소.

## 구조

| 위치 | 역할 | 바꾸는 곳 |
|---|---|---|
| 예약 작업 프롬프트 | 저장소, 리포트 폴더, 날짜 기준, 커밋과 메일 발송 규칙 | 작업 편집 화면 |
| PROMPT.md | 실행이 처음 읽는 진입점. 읽을 파일과 진행 순서 | 저장소 커밋 |
| guide/ | 조사 방법 4개 파일 | 저장소 커밋 |
| reports/YYYY-MM-DD.md | 그날의 리포트 | 예약 실행이 작성 |
| reports/INDEX.md | 다룬 논문의 누적 목록. 중복 제거의 기준 | 예약 실행이 작성 |

## 무엇을 어디서 바꾸나

| 바꾸려는 것 | 위치 |
|---|---|
| 목적, 독자 수준, 문체 | guide/1-principles.md |
| 새 논문 목록과 본문을 여는 경로 | guide/2-access.md |
| 분야, 대상 기간, 분야별 편수, 고르는 기준 | guide/3-selection.md |
| 리포트 틀, 금요일 정리, INDEX의 열, 메일 항목 | guide/4-report.md |
