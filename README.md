![header](https://capsule-render.vercel.app/api?type=waving&height=180&color=gradient&text=Seungeon%20Choi&fontAlign=50&fontAlignY=35&desc=Backend%20Developer&descAlign=50&descAlignY=60)

# 최승언 / Seungeon Choi

안녕하세요.  
**이벤트 기반 아키텍처와 대용량 처리에 관심이 많은 백엔드 개발자 최승언**입니다.

사용자에게 보이지 않는 서버 내부의 흐름을 더 안정적이고, 더 일관되게 만드는 일을 좋아합니다.  
특히 **Kafka 기반 비동기 처리, 정산/알림 파이프라인, 공통 모듈화**에 관심을 두고 프로젝트를 진행해왔습니다.

---

## 🧑‍💻 About Me

- Backend Developer
- Java / Spring 기반 서버 개발
- Kafka, Redis, MySQL을 활용한 비동기 처리와 데이터 일관성 설계에 관심
- 대용량 트래픽과 운영 관점의 백엔드 구조를 고민하는 개발자

---

## 🏫 Education

- **Soonchunhyang University**
  `2020.03 ~ 2026.02`
- **OOPSLA Lab, Soonchunhyang University**
  `2023.03 ~ 2025.06`
- **LG U+ URECA Backend**
  `2025.08 ~ 2026.03`

---

## 📜 Certification

- **Engineer Information Processing** (정보처리기사)
- **SQL Developer (SQLD)**

---

## 🛠 Tech Stack

### Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![QueryDSL](https://img.shields.io/badge/QueryDSL-0769AD?style=for-the-badge&logoColor=white)

### Messaging / Data
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-D92D2A?style=for-the-badge&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

### Infra / DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

### Collaboration
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)

---

## 🚀 Main Projects

### 1. DABOM
> 가족 단위 디지털 사용량 관리 서비스

**DABOM은 여러 저장소로 구성된 프로젝트이며, 아래 3개 레포지토리에 직접 기여했습니다.**

#### - dabom-processor-usage
실시간 사용량 이벤트를 처리하고, 검증 → Redis/Lua 기반 판단 → DB 정산 → 알림 발행까지 수행하는 서비스

#### - lib-kafka
프로젝트 내 Kafka 메시징 규약과 설정을 공통화한 라이브러리

#### - dabom-api-core
가족 단위 디지털 사용량 관리 기능을 제공하는 API 서버

**What I focused on**
- Kafka 기반 이벤트 처리 흐름 설계
- 공통 메시징 라이브러리 분리 및 재사용성 향상
- Redis / DB 역할 분리를 통한 처리 구조 설계
- 알림 발행 안정성을 고려한 비동기 파이프라인 구성
- 운영 지표와 확장성을 고려한 백엔드 구조 고민

**Tech**
`Java` `Spring Boot` `Kafka` `Redis` `MySQL` `Prometheus`

**Repositories**
- [dabom-processor-usage](https://github.com/da-bom/dabom-processor-usage)
- [lib-kafka](https://github.com/da-bom/lib-kafka)
- [dabom-api-core](https://github.com/da-bom/dabom-api-core)

---

### 2. TR1L
> 대용량 통신 요금 명세서 및 알림 발송 시스템

대규모 청구/정산 데이터를 기반으로 고객별 청구서를 생성하고,  
Email / SMS 발송을 **중복 없이 안정적으로 처리**하는 플랫폼입니다.

**What I focused on**
- 대용량 발송 환경을 고려한 비동기 처리 구조 이해 및 구현
- Kafka 기반 발송 요청 / 결과 처리 흐름 설계
- 장애 내성과 중복 방지를 고려한 메시징 구조 고민
- 운영 환경에서 확장성과 비용 효율을 함께 고려한 아키텍처 학습

**Tech**
`Java` `Spring Boot` `Kafka` `PostgreSQL` `Docker` `Prometheus` `Grafana`

**Repository**
- [TR1L-BE](https://github.com/Team-TR1L/TR1L-BE)

---

## 🧩 Algorithm

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=chygold77)](https://solved.ac/chygold77)

---

## 📂 Pinned Repositories

- [dabom-processor-usage](https://github.com/da-bom/dabom-processor-usage)
- [lib-kafka](https://github.com/da-bom/lib-kafka)
- [dabom-api-core](https://github.com/da-bom/dabom-api-core)
- [TR1L-BE](https://github.com/Team-TR1L/TR1L-BE)
- [Tech-Post_BE](https://github.com/MINI-Tech-Post/Tech-Post_BE)

---

## 📫 Contact

- GitHub: [ChoiSeungeon](https://github.com/ChoiSeungeon)
- Email: [chygold06@naver.com](mailto:chygold06@naver.com)
