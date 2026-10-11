<!-- Layout references: anuraghazra/anuraghazra, DenverCoder1/DenverCoder1, zyh3699/awesome-github-readme-profile. Original text and project descriptions. -->

<p align="center">
  <img src="./assets/profile-header.svg" width="100%" alt="Jeayoung · Backend Developer" />
</p>

<h3 align="center">안녕하세요, 백엔드 개발자 정재영입니다.</h3>

<p align="center">
  Java와 Spring Boot로 API와 데이터 처리 기능을 개발합니다.<br />
  매칭 동시성 제어와 Docker 채점 구조 개선 경험이 있습니다.
</p>

<p align="center">
  <a href="https://github.com/jeayoung98?tab=repositories"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&amp;logo=github&amp;logoColor=white" alt="GitHub repositories" /></a>
  <a href="https://solved.ac/jeayoung98"><img src="https://img.shields.io/badge/Solved.ac-17A34A?style=flat-square&amp;logoColor=white" alt="Solved.ac" /></a>
</p>

<br />

### 🔎 Backend Experience

- **동시성 제어** — Redis Lua로 매칭 후보 조회·선점·제거를 원자화했습니다. 5,000명 동시 요청 검증에서 중복 매칭·정원 초과·저장 인원 불일치는 **0건**이었습니다.
- **DB 병목 분석** — `pg_stat_statements`와 실행계획으로 저장 경로를 분석했습니다. 그룹 단위 조회와 Batch Insert를 적용해 SQL 호출을 **155,782회 → 44,360회**로 줄였습니다.
- **실행 구조 개선** — 테스트케이스마다 반복하던 컨테이너 생성·삭제를 제출당 1회로 바꿨습니다. Python 100개 테스트케이스의 채점 시간을 **약 44초 → 13초**로 단축했습니다.

<br />

### 🏆 Awards

| 프로젝트 | 수상 |
| :--- | :--- |
| **[KMBBJ](https://github.com/jeayoung98/KMBBJ_BACKEND)** · 모의 코인 거래 서비스 | **최우수상** |
| **ODY** | **특화 프로젝트 2등** |

<br />

### 📂 Projects

| 프로젝트 | 담당 기능과 구현 |
| :--- | :--- |
| **[SSOJ](https://github.com/jeayoung98/SSOJ)**<br />온라인 저지 채점 서버 | 채점 요청 처리 · Docker 코드 실행 · 결과 판정·저장<br />SSE 진행률 전달, 제출 단위 Batch 채점 구조 |
| **[KMBBJ](https://github.com/jeayoung98/KMBBJ_BACKEND)**<br />모의 코인 거래 서비스 | 자산 기반 매칭 · 대기열 관리 · SSE 알림 · 공통 응답<br />Redis Lua 선점, 그룹 단위 조회·저장 |
| **[AI-CCAS](https://github.com/jeayoung98/AI-CCAS-)**<br />민원 근거 검색 모듈 · 개발 완료 | pgvector 유형별 검색 · 근거 충분성 평가 · 검색 이력 저장<br />유사 사례·유형 기준·공식 안내를 검색해 후속 AI에 전달 |

<br />

<h3 align="center">🛠 Tech Stack</h3>

<p align="center">
  <img src="./assets/skill-icons.svg" width="500" alt="Java, Spring, PostgreSQL, MySQL, Redis, Docker, AWS, Google Cloud" />
</p>

<p align="center">
  <sub>Java · Spring Boot · JPA · PostgreSQL · MySQL · Redis · Docker · AWS · GCP</sub>
</p>

<br />

### 🌱 Learning

[알고리즘·SQL 풀이](https://github.com/jeayoung98/CodingTest) &nbsp; / &nbsp; [Java](https://github.com/jeayoung98/JavaStudy) &nbsp; / &nbsp; [Spring](https://github.com/jeayoung98/SpringStudy)

<p align="center">
  <a href="https://solved.ac/jeayoung98"><img src="https://mazassumnida.wtf/api/v2/generate_badge?boj=jeayoung98" width="320" alt="Solved.ac 프로필" /></a>
</p>
