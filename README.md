<div align="center">

<img src="./assets/profile-header.svg" alt="최명헌 · AI Backend Service Development" width="100%" />

### 프로젝트로 문제를 발견하고, 서비스로 해결합니다

**AI · Backend · Web · Data · Deployment**

</div>

---

## 프로젝트 포트폴리오

현장과 일상에서 발견한 불편을 웹 서비스로 풀어내는 프로젝트를 진행해 왔습니다.  
물품·재고 관리, 사내 업무 자료와 실행 흐름, 태권도 동작 분석, 제작·판매 수익 분석까지 서로 다른 문제를 데이터와 사용 흐름 중심으로 구현했습니다.

| 프로젝트 | 해결하려는 문제와 구현 내용 |
| --- | --- |
| [Restok](https://github.com/chl4890620123-collab/Restok-Rangchain) | 물품 등록부터 사용·판매·기부·재활용·폐기까지 관리하는 생애주기 플랫폼 |
| [Hub](https://github.com/chl4890620123-collab/hub) | 문서·회의 자료 검색을 근거 확인, 업무 배정, 제출·승인까지 연결하는 사내 업무 허브 |
| [AITM](https://github.com/chl4890620123-collab/Aitm) | 영상에서 태권도 동작을 측정하고 결과 근거와 코칭을 제공하는 서비스 |
| [Maple Craft Analytics](https://github.com/chl4890620123-collab/maple) | 제작비·수수료·판매 기록을 계산해 실제 수익과 추천을 분석하는 도구 |
| [Server](https://github.com/chl4890620123-collab/Server) | 여러 앱의 Docker 운영 구성, 배포와 검증을 관리하는 인프라 저장소 |

### 프로젝트 전반에서 다룬 내용

- 사용자 문제와 업무 흐름을 정리하고, 화면에서 다음 행동이 보이도록 설계
- React 화면과 Spring Boot·FastAPI API를 연결하고 데이터 저장 구조 구성
- AI를 기능의 목적 자체로 두기보다 검색·분석·입력 보조에 활용
- 역할과 권한, 원문 근거, 데이터 보존, 운영 비밀 설정을 고려
- Docker와 CI/CD로 빌드·검증·배포 흐름을 구성

---

## 대표 프로젝트 자세히 보기

### 📦 [Restok — 물품 생애주기 관리](https://github.com/chl4890620123-collab/Restok-Rangchain)

물류·재고 업무에서 본 낭비와 불편을 바탕으로 만든 URL 중심 플랫폼입니다.

- 입고·출고와 상품 정보를 기록하고, 사용자가 기본값을 수정해 상세 정보를 관리
- 시간 기준 처리와 자동 정리를 포함한 반자동 관리 흐름
- 거래처·판매처 등의 URL을 사용자가 직접 등록해 처리 경로를 선택
- 대시보드와 상세 화면에서 보유 물품과 처리 이력 확인
- 영수증 분석과 보유 데이터 기반 AI 보조 기능

**기술:** Java · Spring Boot · React · FastAPI · Gemini · MariaDB · Docker

### 🧭 [Hub — 사내 업무 AI 허브](https://github.com/chl4890620123-collab/hub)

흩어진 문서·회의 자료를 검색에서 실제 업무 처리까지 연결합니다.

- 검색 답변을 원문 근거와 연결해 사용자가 확인하도록 구성
- AI 후보 검토, 담당자 지정, 결과 제출, 관리자 승인으로 이어지는 업무 흐름
- Spring Boot 백엔드, React·TypeScript 화면, FastAPI AI 서비스 분리
- Docker와 GitHub Actions를 활용한 검증·배포 구성

**기술:** Java · Spring Boot · React · TypeScript · Python · FastAPI · PostgreSQL · Docker · GitHub Actions

### 🥋 [AITM — AI 태권도 동작 분석](https://github.com/chl4890620123-collab/Aitm)

영상의 포즈와 관절 좌표를 분석해 태권도 동작을 측정하고 코칭 정보를 제공합니다.

- MediaPipe와 OpenCV 기반 동작·관절 분석
- 무릎 각도, 회전, 타이밍, 착지 등의 측정값으로 점수 산출
- 분석 신뢰도에 따라 결과 확정과 검토 필요 상태 구분
- 포즈 오버레이와 문제 시점 느린 재생으로 결과 근거 확인

**기술:** Java · Spring Boot · React · Python · FastAPI · MediaPipe · OpenCV · MariaDB · Docker

### 🍁 [Maple Craft Analytics — 제작·판매 분석](https://github.com/chl4890620123-collab/maple)

메이플스토리 제작품의 재료비, 판매가와 실제 거래 이력을 관리합니다.

- 레시피 기반 제작비, 수수료와 예상 수익 계산
- 재료·판매 가격 이력과 실제 제작·판매 기록 저장
- 예상 수익과 실현 수익을 비교해 추천을 보정
- SQLite 회귀 테스트, MariaDB 통합 테스트, Docker 빌드 CI 구성

**기술:** Python · FastAPI · MariaDB · SQLite · Docker · GitHub Actions

### 🖥️ [Server — 중앙 운영 인프라](https://github.com/chl4890620123-collab/Server)

앱 코드와 운영 환경을 분리하고, 여러 서비스의 배포 구성을 관리합니다.

- Docker Compose, Caddy, 배포·검증 스크립트 관리
- 운영 데이터와 비밀 설정을 소스 코드에서 분리
- 배포 전후 상태를 점검하는 검증 흐름 구성

**기술:** Docker Compose · Caddy · GitHub Actions · PowerShell

---

## 경력

### 수호랑캠프 | 교관
**2023.10–2024.03**

### 에스텍시스템 | 보안 사원
**2021.06–2022.12**

### 쿠팡 | 물류센터 업무
**2019.08–2019.11** · IB · OB · ICQA · HUB

### GS25 암사시장점 | 편의점 근무
**2018.01–2018.12**

### GS25 암사점 | 판매원·매니저
**2014.11–2016.03**

---

## 학력 및 교육

- **세한대학교 태권도학과 졸업** · 2010.02–2019.02
- **선사고등학교 문과 졸업**
- **기업연계형 ChatGPT 활용 및 DevOps 개발자 부트캠프** · MBC아카데미 컴퓨터학원 · 2025.10–2026.04  
  Java, Python, SQL, React·Vue.js, Spring Boot, CI/CD, Git
- **ICT 컴퓨터 활용 기술** · 동부교육기술원 · 2024.09–2025.01  
  Linux, vi, VMware 기반 서버 구축, PowerPoint·Excel
- **EST AI 챌린저스 1기** · 이스트소프트 · 2026.07–2026.08  
  Python AI 실무 교육

---

## 자격 및 활동

- 정보기술자격(ITQ) 한글엑셀 A등급 · 2025.01.02 · 한국생산성본부
- 정보기술자격(ITQ) 한글파워포인트 A등급 · 2025.01.02 · 한국생산성본부
- 리눅스마스터 2급 필기 · 2024.11.05
- 이스트소프트 대외 활동 · 2026.08–2026.09
- 태권도 시범단 · 체코 · 2015.02.12–2015.02.22
- 태권도 시범단 · 호주 · 2017.01.21–2017.01.30
- 태권도 시범단 · 미국 · 2019.02.01–2019.02.10
- 육군 병장 만기 전역 · 2019.11–2021.05

---

## 개발자로서의 방향

현장 경험을 바탕으로 반복되는 불편을 찾고, 사용자가 이해하기 쉬운 서비스 흐름으로 바꾸는 데 관심이 있습니다. Restok에서는 물품 관리 경험을 입고·출고, 사용자 지정 URL, 이력 관리와 AI 보조 기능으로 구체화했습니다.

협업에서는 회의 내용을 정리해 공유하고, 주석과 문서로 코드의 의도와 동작을 설명하는 것을 중요하게 생각합니다. AI가 생성한 코드도 그대로 적용하지 않고 로직·중복·보안 설정을 확인하며, 운영 단계에서 관리할 수 있는 구조로 다듬고 있습니다.

---

## 기술 및 역량

- **백엔드:** Java · Spring Boot · JSP · Python · FastAPI
- **프론트엔드:** React · Vue.js · JavaScript · TypeScript · HTML · CSS
- **데이터베이스:** SQL · MariaDB · PostgreSQL · SQLite
- **AI·데이터 처리:** Gemini · LangChain · RAG · MediaPipe · OpenCV · 문서·음성 처리
- **배포·협업:** Docker · Docker Compose · CI/CD · Git · GitHub Actions
- **개발 방식:** 사용자 흐름 설계 · API와 데이터 연동 · 권한·보안 고려 · 테스트와 배포 검증

---

<div align="center">

**프로젝트 코드와 상세 내용은 각 저장소에서 확인할 수 있습니다.**

[Hub](https://github.com/chl4890620123-collab/hub) · [AITM](https://github.com/chl4890620123-collab/Aitm) · [Restok](https://github.com/chl4890620123-collab/Restok-Rangchain) · [Maple](https://github.com/chl4890620123-collab/maple) · [Server](https://github.com/chl4890620123-collab/Server)

</div>
