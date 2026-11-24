# 3. 논문 선정

## 분야

| 분야 | 범위 |
|---|---|
| ASR | end-to-end ASR, RNN-T, CTC, Whisper 계열, multilingual ASR, diarization |
| SpeechLLM | speech-language model, spoken dialogue, voice agent, LLM을 이용한 음성 이해와 생성 |
| Speech Foundation Model | speech SSL, speech tokenizer, speech representation learning, audio pre-training |

여러 분야에 걸치는 논문은 가장 가까운 분야 하나에만 실을 것.

## 대상

실행일 기준 최근 14일 이내에 arXiv(eess.AS, cs.SD, cs.CL)에 올라온 논문과, 그 기간에 채택이 발표된 학회(Interspeech, ICASSP, ICML, ICLR, NeurIPS) 논문.

## 중복 제거

- 후보마다 arXiv ID를 INDEX.md에서 검색(grep)하고, 이미 있는 논문은 제외할 것. arXiv ID가 없는 논문은 제목의 핵심 구절로 검색할 것
- 기억이나 훑어본 것으로 판단하지 말고, 반드시 검색 결과로 확인할 것
- INDEX.md가 없으면 빈 표로 시작할 것
- 이미 다룬 논문의 개정판이나 학회 채택 소식은 새 논문으로 치지 말 것

## 고르는 기준

분야별 2편. 고를 논문이 모자라면 있는 만큼만 싣고 억지로 채우지 말 것.

- 우선순위: 학회 채택이 확인된 논문, 코드나 모델을 공개한 논문, 주요 연구 그룹의 논문, 새 문제나 데이터셋을 제시했거나 널리 쓰이는 벤치마크에서 뚜렷한 결과를 낸 논문
- 각 분야의 핵심 주제를 우선하고, 음성 기술 자체가 목적이 아닌 응용(의료 진단, 뇌 신호 분석 등)은 다른 후보가 없을 때만 고를 것
- 같은 세부 주제의 논문이 하루에 몰리지 않게 할 것
- 고를 논문이 없는 분야는 "새 논문 없음"으로 적을 것
- 세 분야 모두 없으면 리포트와 메일을 "오늘은 새로운 논문이 없습니다"로 짧게 마무리할 것
