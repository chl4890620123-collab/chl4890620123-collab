<div align="center">

<img src="./assets/profile-header.svg" alt="최명헌 · AI Backend Service Development" width="100%" />

### 프로젝트로 문제를 발견하고, 서비스로 해결합니다

**AI · Backend · Web · Data · Safety · Deployment**

</div>

---

## 프로젝트 포트폴리오

현장·가족·조직에서 발견한 문제를 웹 서비스와 운영 가능한 시스템으로 풀어내고 있습니다.  
AI 서비스뿐 아니라 가족 안전, 건설 현장 안전, 시민 서비스, 물류·재고, 동작 분석, 클라우드 배포까지 여러 주제를 다뤘습니다.

| 분야 | 프로젝트 | 만든 것 |
| --- | --- | --- |
| 가족·디지털 안전 | [닿음 (Dahum)](https://github.com/EST-AI-Challengers-31/saver) | 부모님의 스마트폰 위험 정보를 가족이 함께 확인하고 이해하기 쉬운 대응 행동으로 연결하는 모바일 웹 MVP |
| 건설 현장 안전 | [SafeStack Weather Guard](https://github.com/chl4890620123-collab/Star-Developer-2648) | 현장 자재·고정 상태와 풍속 예보를 결합해 강풍에 따른 적재물 위험을 확인하는 시스템 |
| 시민 서비스 | 서울이어 | 돌봄·복지·일자리·문화·안전 정보를 시민의 상황에 맞춰 찾고, 접근성 높은 안내와 절차를 제공하는 서비스 프로토타입 |
| 사내 업무 AI | [Hub](https://github.com/chl4890620123-collab/hub) | 문서·회의 검색을 원문 근거 확인, 담당자 업무, 제출·관리자 승인까지 연결 |
| 이동 현장 지식 | [MOVE AI](https://github.com/HyejiShin-20/MOVEAI) | 기사님의 음성·텍스트 경험을 구조화·검수해 조건에 맞는 현장 지식으로 다시 제공 |
| 태권도 동작 분석 | [AITM](https://github.com/chl4890620123-collab/Aitm) | 영상의 관절 움직임을 측정하고 근거와 함께 점수·코칭을 제공 |
| 물품 생애주기 | [Restok](https://github.com/chl4890620123-collab/Restok-Rangchain) | 물품 등록부터 사용·판매·기부·재활용·폐기까지 이력 관리 |
| 제작·판매 분석 | [Maple Craft Analytics](https://github.com/chl4890620123-collab/maple) | 제작비·수수료·예상 수익과 실제 판매 이력을 계산·분석 |
| 클라우드·DevOps | [한스푼](https://github.com/chl4890620123-collab/hanspoon-frontend) | AWS 인프라, 보안 설정, CI/CD와 헬스체크 기반 배포 흐름 구성 |
| 운영 인프라 | [Server](https://github.com/chl4890620123-collab/Server) | 여러 앱의 Docker 운영 구성과 배포·검증을 관리 |

### 프로젝트 전반에서 다룬 내용

- 문제와 사용자 흐름을 정리하고, 화면에서 다음 행동이 보이도록 설계
- React 화면과 Spring Boot·FastAPI API를 연결하고 데이터 흐름 구성
- 현장·문서·영상 입력을 검색·분석 가능한 데이터로 정리
- AI가 만든 결과를 바로 확정하지 않고 근거와 사람의 검토를 거치도록 설계
- 위험도는 수치 계산과 근거를 함께 보여 주고, 불확실한 상태는 안전하다고 단정하지 않도록 처리
- Docker와 CI/CD로 빌드·검증·배포 흐름 구성

---

## 프로젝트 상세

### 🤝 [닿음 (Dahum) — 가족과 함께 확인하는 스마트폰 안전](https://github.com/EST-AI-Challengers-31/saver)

부모님의 스마트폰에서 발견한 위험 정보를 자녀가 함께 확인하고, 이해하기 쉬운 대응 행동으로 이어 주는 모바일 웹 MVP입니다.

- React 화면, Spring Boot 백엔드, FastAPI AI 서비스, MariaDB를 분리해 구성
- GitHub Actions에서 Docker 이미지를 빌드해 GHCR에 게시하고, 서버는 SHA 태그 이미지를 받아 실행
- Docker Compose와 Caddy를 연결하고, 배포 뒤 시스템 상태와 health check 확인
- 판단 근거가 부족한 정보는 안전하다고 표시하지 않도록 데모 확인 흐름 구성

**기술:** React · Spring Boot · FastAPI · MariaDB · Docker Compose · GitHub Actions · GHCR

### 🌬️ [SafeStack Weather Guard — 건설 현장 풍속 안전](https://github.com/chl4890620123-collab/Star-Developer-2648)

건설 현장의 적재 위치와 자재 정보에 기상 예보를 더해 강풍에 따른 낙하·비산 위험을 확인하는 프로젝트입니다.

- 현장·층·위치, 자재 규격·무게·수량, 고정 상태와 사진을 기준 데이터로 관리
- 현재·예보 풍속 변화를 반영해 위험을 다시 계산하고 민감도와 불확실성 확인
- 위험 위치 수, 원인 자재, 사고 유형, 근거와 권장 조치를 대시보드로 제공
- 풍속만 바뀌는 경우에는 LLM 호출 없이 수치 계산으로 재분석

**기술:** TypeScript · 기상 API · Python 분석 검증

### 🏙️ 서울이어 — 시민 생활·안전 서비스 통합

돌봄·복지·일자리·문화·안전 정보를 시민 관점에서 찾고, 필요한 다음 절차로 이어 주는 통합 서비스 프로토타입입니다.

- 여러 기관과 서비스에 흩어진 정보를 분야별로 모아 탐색
- 고령자·장애인도 쓰기 쉽도록 모바일 화면과 큰 터치 영역을 고려
- 긴급 연락처와 공식 안내, 단계별 안전 절차 제공
- 자동 제출이나 신청을 임의로 진행하지 않고 사용자가 확인하는 흐름

**중점:** 시민 중심 UX · 공공데이터 활용 · 접근성 · 안전한 절차 안내

### 🧭 [Hub — 사내 업무 AI 허브](https://github.com/chl4890620123-collab/hub)

흩어진 문서·회의 자료의 검색을 실제 업무 처리까지 연결하는 플랫폼입니다.

- 검색 답변을 원문 근거와 연결해 사용자가 확인하도록 구성
- AI 후보 검토, 담당자 지정, 결과 제출, 관리자 승인으로 이어지는 업무 흐름
- Spring Boot 백엔드, React·TypeScript 화면, FastAPI AI 서비스 분리
- Docker와 GitHub Actions를 활용한 검증·배포 구성

**기술:** Java · Spring Boot · React · TypeScript · Python · FastAPI · PostgreSQL · Docker · GitHub Actions

### 🚚 [MOVE AI — 현장 경험 지식화](https://github.com/HyejiShin-20/MOVEAI)

기사님의 음성·텍스트 경험을 검수 가능한 지식으로 바꾸고, 상황에 맞는 정보를 다시 제공하는 프로젝트입니다.

- 현장 제보를 STT와 추출 과정을 거쳐 위치·차량·시간·주의사항 단위로 구조화
- 원문에 없는 숫자나 경로를 보태지 않고, 사람이 확인한 지식만 안내에 사용
- 명확한 조건은 규칙으로, 맥락과 의미는 벡터 검색으로 처리하는 Hybrid RAG 방향
- 프로젝트에서 백엔드 연결, Docker 구성, CI/CD와 배포·운영 흐름을 다룸

**기술:** React · Spring Boot · FastAPI · MariaDB · STT · Embedding · Hybrid RAG · Docker

### 🥋 [AITM — AI 태권도 동작 분석](https://github.com/chl4890620123-collab/Aitm)

영상의 포즈와 관절 좌표를 분석해 태권도 동작을 측정하고 코칭 정보를 제공합니다.

- MediaPipe와 OpenCV 기반 동작·관절 분석
- 무릎 각도, 회전, 타이밍, 착지 등의 측정값으로 점수 산출
- 분석 신뢰도에 따라 결과 확정과 검토 필요 상태 구분
- 포즈 오버레이와 문제 시점 느린 재생으로 결과 근거 확인

**기술:** Java · Spring Boot · React · Python · FastAPI · MediaPipe · OpenCV · MariaDB · Docker

### 📦 [Restok — 물품 생애주기 관리](https://github.com/chl4890620123-collab/Restok-Rangchain)

물류·재고 업무에서 본 낭비와 불편을 바탕으로 만든 URL 중심 플랫폼입니다.

- 입고·출고와 상품 정보를 기록하고, 사용자가 기본값을 수정해 상세 정보를 관리
- 시간 기준 처리와 자동 정리를 포함한 반자동 관리 흐름
- 거래처·판매처 등의 URL을 사용자가 직접 등록해 처리 경로를 선택
- 대시보드와 상세 화면에서 보유 물품과 처리 이력 확인
- 영수증 분석과 보유 데이터 기반 AI 보조 기능

**기술:** Java · Spring Boot · React · FastAPI · Gemini · MariaDB · Docker

### 🍁 [Maple Craft Analytics — 제작·판매 분석](https://github.com/chl4890620123-collab/maple)

메이플스토리 제작품의 재료비, 판매가와 실제 거래 이력을 관리합니다.

- 레시피 기반 제작비, 수수료와 예상 수익 계산
- 재료·판매 가격 이력과 실제 제작·판매 기록 저장
- 예상 수익과 실현 수익을 비교해 추천을 보정
- SQLite 회귀 테스트, MariaDB 통합 테스트, Docker 빌드 CI 구성

**기술:** Python · FastAPI · MariaDB · SQLite · Docker · GitHub Actions

### ☁️ [한스푼 — AWS Cloud·DevOps](https://github.com/chl4890620123-collab/hanspoon-frontend) · [Backend](https://github.com/chl4890620123-collab/hanspoonbackend)

웹 애플리케이션의 AWS 인프라와 자동 배포 흐름을 구성한 프로젝트입니다.

- Terraform으로 EC2·RDS·네트워크와 보안 그룹 구성
- GitHub Actions의 빌드와 배포를 분리해 운영 서버의 빌드 부담을 줄임
- Nginx·systemd·Health Check 기반 실행·릴리스 확인
- Secret과 네트워크 접근을 분리해 DB를 외부에서 직접 공개하지 않도록 구성

**기술:** AWS · Terraform · EC2 · RDS · GitHub Actions · Nginx · systemd

### 🖥️ [Server — 중앙 운영 인프라](https://github.com/chl4890620123-collab/Server)

앱 코드와 운영 환경을 분리하고 여러 서비스의 배포 구성을 관리합니다.

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
- **배포·협업:** AWS · Terraform · Docker · Docker Compose · CI/CD · Git · GitHub Actions
- **개발 방식:** 사용자 흐름 설계 · API와 데이터 연동 · 권한·보안 고려 · 테스트와 배포 검증

---

<div align="center">

**프로젝트 코드와 상세 내용은 각 저장소에서 확인할 수 있습니다.**

[닿음](https://github.com/EST-AI-Challengers-31/saver) · [SafeStack](https://github.com/chl4890620123-collab/Star-Developer-2648) · [Hub](https://github.com/chl4890620123-collab/hub) · [AITM](https://github.com/chl4890620123-collab/Aitm) · [Restok](https://github.com/chl4890620123-collab/Restok-Rangchain) · [Maple](https://github.com/chl4890620123-collab/maple)

</div>
