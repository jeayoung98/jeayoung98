# 정재영 | Backend Developer

Java와 Spring Boot로 백엔드를 개발합니다.  
동시 요청에서 발생하는 매칭 오류와 채점 서버의 반복 실행 비용을 분석하고 개선했습니다.

## 대표 프로젝트

### [SSOJ · 온라인 저지 채점 서버](https://github.com/jeayoung98/SSOJ)

C++·Java·Python으로 제출한 코드를 실행하고 채점 결과를 반환하는 서비스입니다.

- **개발:** Spring Boot 기반 채점 요청 처리, Docker 코드 실행, SSE 진행률 전달
- **개선:** 테스트케이스마다 반복하던 컨테이너 생성·삭제를 제출당 1회 실행으로 변경
- **결과:** 기존 Python 측정 기록에서 전체 채점 시간 약 44초 → 13초
- [채점 구조와 성능 개선](https://github.com/jeayoung98/SSOJ#채점-성능-개선)

### [KMBBJ · 모의 코인 거래 서비스](https://github.com/jeayoung98/KMBBJ_BACKEND)

가상 자산으로 코인 거래를 연습하고, 자산이 유사한 사용자끼리 매칭되어 게임을 진행하는 서비스입니다.

- **담당:** 매칭 시스템, 알림, 공통 응답 처리
- **개선:** Redis Sorted Set과 Lua Script로 후보 조회·선점·제거를 원자적으로 처리하고, Batch Insert로 DB 저장 비용 개선
- **결과:** 5,000명 동시 요청의 로컬 서비스 레이어 벤치마크에서 평균 처리 시간 12.74초 → 3.48초
- [매칭 대기열 개선 과정과 검증](https://github.com/jeayoung98/KMBBJ_BACKEND/blob/main/docs/troubleshooting/matching-queue-optimization.md)

## 개발 중

### [AI-CCAS · 민원 안내를 위한 근거 검색 모듈](https://github.com/jeayoung98/AI-CCAS-)

구조화된 민원 내용을 받아 유사 사례·유형 기준·공식 안내 문서를 검색하고, 후속 AI가 사용할 근거를 반환하는 백엔드 모듈입니다.

- PostgreSQL·pgvector 기반 유형별 벡터 검색
- 검색 결과의 근거 충분성 평가와 검색 이력 저장
- 검색 임계값은 현재 데모용이며, 실제 데이터 기반 정확도 평가는 진행 전입니다.

## 기술 스택

| 분야 | 기술 |
|---|---|
| Backend | Java, Spring Boot, Spring Data JPA |
| Database | PostgreSQL, MySQL, Redis, pgvector |
| Infrastructure | Docker, AWS, GCP |

## 학습 기록

[알고리즘 풀이](https://github.com/jeayoung98/CodingTest) · [Java 학습](https://github.com/jeayoung98/JavaStudy) · [Spring 학습](https://github.com/jeayoung98/SpringStudy)

[![Solved.ac 프로필](https://mazassumnida.wtf/api/v2/generate_badge?boj=jeayoung98)](https://solved.ac/jeayoung98)

