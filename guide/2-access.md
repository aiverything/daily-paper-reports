# 2. 접근

검색 결과의 요약만 보고 쓰지 말 것. 논문마다 초록 페이지와 본문을 직접 열어 확인할 것.

## 경로

실행 환경의 네트워크 정책에 따라 열리는 곳이 달라. 아래를 시도하고, 열리는 경로를 쓸 것.

| 용도 | 경로 |
|---|---|
| 새 논문 목록 | export.arxiv.org/api/query (cat:eess.AS, cat:cs.SD, cat:cs.CL을 제출일 내림차순으로 조회). 열 수 없으면 웹 검색 |
| 제목, 저자, 제출일, 학회 채택 여부 | arxiv.org/abs/ID (학회 채택은 Comments 항목) |
| 본문 | arxiv.org/html/ID, arxiv.org/pdf/ID |
| 학회 논문집 | Interspeech: isca-archive.org. ICLR, NeurIPS, ICML: openreview.net, proceedings.mlr.press, proceedings.neurips.cc |
| 코드와 모델 | huggingface.co. github.com 페이지가 열리지 않으면 `https://raw.githubusercontent.com/소유자/저장소/HEAD/README.md` |

- 셸의 curl과 페이지 열기 도구를 모두 시험할 것. PDF는 pdftotext나 pypdf로 텍스트로 바꿔 읽을 것
- 한두 곳이 막혔다고 전체가 막혔다고 단정하지 말 것. 열어 보지 않은 사이트를 막혔다고 쓰지 말 것
- 본문은 서론, 방법, 주요 결과표까지 읽을 것. 부록은 읽지 않아도 돼

## 열 수 없을 때

- 본문을 열지 못한 논문은 고르지 말 것. 그 분야에 다른 후보가 없을 때만 초록만으로 쓰고 "초록 기준"이라고 표시할 것
- arXiv가 전혀 열리지 않는 날은 웹 검색으로 확인한 내용만 쓰고, 리포트 맨 위에 그 사실을 밝힐 것
