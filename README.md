# Hi, I'm Lee Do Kwon (이도권) 👋
### Generative AI Service Developer

동료가 각자의 일에 집중할 수 있게 돕는 AI 도구를 만드는 개발자입니다.
현재 **SKALA**(SK AX 생성형 AI 서비스 개발 과정)에서 LLM 에이전트, RAG, MSA 백엔드를 직접 구현하고 있습니다.

### 🔥 Currently

🤖 **SKALA 4기 (SK AX)** — 생성형 AI 서비스 개발 과정 참여 중 (2026.07 ~)
생성형 AI, sLLM 파인튜닝, Docker와 Kubernetes 기반 MSA 백엔드, 모델 서빙과 AIOps를 학습하고 팀 프로젝트로 구현하고 있습니다.

### 🎓 SKALA Projects

🤝 **[KV Cache 기술 비교 평가 시스템 (TurboQuant vs ITME)](https://github.com/dokwon33/capstone-v1)** — 6인 팀
LangGraph 멀티에이전트와 Agentic RAG로 KV Cache 최적화 기술을 SW와 HW 관점에서 근거 기반으로 비교 평가합니다.
- 담당: LangGraph 상태와 라우팅 설계, 에이전트 간 공통 계약, 재시도 정책과 SQLite 체크포인트 기반 재개, 실패 기록 처리
- LLM이 출처 URL을 직접 쓰지 않고 검색 결과 번호만 고르게 해, 코드가 실제 출처를 연결하도록 설계

⚡ **[VoltGo — 전기차 충전 대기시간 활용 에이전트](https://github.com/dokwon33/voltgo)** — 6인 팀
충전이 끝나기 전 다녀올 식사, 쇼핑 장소를 골라 동선과 복귀 시각을 계획하는 LangChain AI 에이전트입니다.
- 담당: TMAP 장소 검색(주변검색, 통합검색), 카테고리 매핑, 남은 충전 시간 기준 반경 자동 필터, 장소 검색 도구와 충전소 조회 도구
- 시간 계산은 LLM 추론 대신 순수 함수로 처리해 같은 입력에 항상 같은 결과가 나오도록 구현

🏗️ **[PoCket — 테스트베드 실증 매칭 플랫폼](https://github.com/dokwon33/PoCket)** — 팀 프로젝트
PoC 공간을 가진 사업장과 실증이 필요한 스타트업을 연결하는 MSA 기반 B2B 매칭 서비스입니다.
- 담당: FastAPI review-service 신규 개발(JWKS 토큰 검증, Swagger 명세), Docker Compose 11개 컨테이너 인프라 기동, API 명세
- 제공된 서비스는 수정하지 않고 Kafka 비동기 이벤트로 연결해 기능을 확장

### 🚀 Projects

📝 **[GitHub PR 기반 퀴즈 서비스](https://github.com/no-dept)** — 컴퓨터과학종합설계(캡스톤), 2026-1학기, 4인 팀 팀장
AI가 생성한 코드를 이해 없이 병합하며 쌓이는 "지식 부채"를 줄이기 위해, PR이 올라오면 LLM이 변경 코드 이해도 퀴즈를 만들고 통과해야 Merge되는 서비스입니다.
- 담당: 팀장, React 대시보드와 데이터 시각화, GitHub OAuth 로그인, 큐 메시지 공용 스키마 저장소 분리 제안
- 구성: FastAPI + AWS Lambda 백엔드, Webhook과 SQS 이벤트 파이프라인, 멀티 레포
- 성과: 5개 평가 항목 개발 목표치 모두 달성(웹훅 응답 평균 0.45초, 퀴즈 생성 평균 18.3초 등), 개발자 20명 대상 SUS 82점

📚 **[학습 점검 퀴즈 도구](https://github.com/dokwon33/knowledge-recall)** — 개인 도구
학습 노트(Word, Markdown, 노션)로 자기 점검 퀴즈를 만드는 로컬 도구입니다. 문항마다 근거가 원문에 실제로 있는지 코드가 검증해 할루시네이션을 구조적으로 차단하고, 퀴즈를 못 만드는 구간은 "정리 갭 카드"로 표시합니다. 간격 반복(Leitner) 기반 복습을 지원합니다.

📊 **[KBO 로스터 트래커](https://github.com/dokwon33/kbo-roster)** — 운영 중
KBO 1군 등록과 말소 현황을 자동 수집해 구단별 로스터와 선수별 이력을 보여주는 서비스입니다. Django 기반으로 Render에 배포했고, LLM 뉴스 요약과 MCP 도구 인터페이스를 제공합니다.

🍚 **[서울시립대 맛집지도](https://github.com/UOSense)** — 소프트웨어공학, 2024-2학기
Kotlin 안드로이드 앱 + Spring Boot 백엔드

📖 **[영어 모의고사 DB 및 퀴즈 웹페이지](https://github.com/jaewon-ju/InternetProgramming_Team_J)** — 인터넷프로그래밍, 2023-2학기
PHP 기반 문제 DB, 로그인, 게시판, 랭킹 기능

### 🔬 Research — NGWN Lab, 서울시립대

**[NGWN Lab](https://ngwn.uos.ac.kr/people)** · 학부연구생 (2025.06 ~ 2026.06)

6G 저궤도 위성 네트워크의 지연 감소를 위한 연구과제에 참여했습니다.
- 이종 그래프 신경망(HetGNN) 기반 채널 상태 예측 모델 설계와 구현, HARQ 재전송 예측으로 확장
- 위성 간 경로 설정에 Viterbi 구조를 적용해 구현과 실험 진행, 전체 지연에서 전파 지연이 지배적이라는 결과 원인 분석
- 저궤도 위성 측위 과제 선행 문헌 조사

### 🛠 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?logo=langgraph&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?logo=vuedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white)

### 📫 Contact

📧 Email: zang03@uos.ac.kr
