# 명헌 | AI·백엔드 중심 서비스 개발

AI 기능을 실제 업무 흐름에 연결하고, 사용자가 계속 쓸 수 있는 웹 서비스로 만드는 데 관심이 있습니다.  
기획부터 화면과 API, 데이터 처리, 배포·운영 구조까지 이어지는 프로젝트를 만들고 개선합니다.

- **관심 분야:** AI 서비스, 백엔드 개발, 업무 자동화, 데이터 처리, 배포·운영
- **주요 기술:** Java, Spring Boot, Python, FastAPI, React, TypeScript, MariaDB, PostgreSQL, Docker
- **활동:** 개인 및 협업 프로젝트
- **연락:** GitHub 프로필을 통해 메시지를 보내 주세요.

---

## 대표 프로젝트

### [Hub — 사내 업무 AI 허브](https://github.com/chl4890620123-collab/hub)

문서와 회의 자료를 검색하는 데서 끝나지 않고, 근거 확인부터 업무 배정과 결과 검토까지 연결하는 업무 플랫폼입니다.

- 문서·회의·연결 서비스의 자료를 검색하고, 답변을 원문 근거와 연결하는 흐름
- AI가 만든 업무 후보를 검토한 뒤 담당자 지정, 제출, 관리자 승인으로 이어지는 역할 기반 업무 흐름
- Spring Boot 백엔드, React·TypeScript 웹 화면, FastAPI AI 서비스를 나눈 구조
- Docker와 GitHub Actions를 이용한 검증·배포 구성

**기술:** Java · Spring Boot · React · TypeScript · Python · FastAPI · PostgreSQL · Docker · GitHub Actions

### [AITM — AI 태권도 동작 분석](https://github.com/chl4890620123-collab/Aitm)

영상에서 포즈와 관절 좌표를 분석하고, 측정 기준과 결과 근거를 함께 보여 주는 태권도 코칭 보조 서비스입니다.

- MediaPipe와 OpenCV를 활용한 동작·관절 분석
- 무릎 각도, 회전, 타이밍, 착지 등 측정값을 기준으로 점수 계산
- 신뢰도가 낮은 분석은 결과를 확정하지 않고 검토가 필요한 상태로 구분
- 문제 시점의 영상과 포즈 오버레이를 확인할 수 있는 결과 흐름

**기술:** Java · Spring Boot · React · Python · FastAPI · MediaPipe · OpenCV · MariaDB · Docker

### [Restok — 물품 생애주기 관리](https://github.com/chl4890620123-collab/Restok-Rangchain)

물품의 등록부터 사용, 판매, 기부, 재활용, 폐기까지 이력을 기록하고 관리하는 플랫폼입니다.

- 외부 서비스를 URL로 등록하는 방식으로 다양한 처리 경로 지원
- 영수증 분석과 보유·처리 이력 기반 AI 보조 기능
- React, Spring Boot, FastAPI를 분리하고 Docker 환경에서 연결
- 로그인 사용자별 물품 접근과 운영 데이터 분리를 고려한 구조

**기술:** Java · Spring Boot · React · FastAPI · Gemini · MariaDB · Docker

### [Maple Craft Analytics — 제작·판매 분석](https://github.com/chl4890620123-collab/maple)

메이플스토리 전문기술 제작품의 재료비와 판매 기록을 관리하고 실제 수익을 분석하는 프로젝트입니다.

- 재료·판매 가격과 가격 변경 이력 관리
- 레시피 기반 제작비, 수수료, 예상 수익 계산
- 실제 제작·판매 기록을 바탕으로 예상과 실현 수익 비교
- SQLite 회귀 테스트와 MariaDB 통합 테스트를 포함한 CI 구성

**기술:** Python · FastAPI · MariaDB · SQLite · Docker · GitHub Actions

### [Server — 중앙 운영 인프라](https://github.com/chl4890620123-collab/Server)

여러 애플리케이션의 운영 구성을 관리하는 인프라 저장소입니다.

- 앱 코드와 운영 환경 설정의 책임 분리
- Docker Compose, Caddy, 배포·검증 스크립트 관리
- 운영 데이터와 비밀 설정을 소스 코드에서 분리
- 배포 전후 상태와 애플리케이션·인프라 변경을 확인하는 흐름

**기술:** Docker Compose · Caddy · GitHub Actions · PowerShell

---

## 기술

| 분야 | 사용 기술 |
| --- | --- |
| 백엔드 | Java, Spring Boot, Python, FastAPI |
| 프론트엔드 | React, TypeScript, JavaScript, HTML, CSS |
| 데이터베이스 | MariaDB, PostgreSQL, SQLite |
| AI·데이터 | MediaPipe, OpenCV, LangChain, RAG, 문서·음성 처리 |
| 배포·협업 | Docker, Docker Compose, GitHub Actions, Git |

---

## 개발할 때 중요하게 보는 점

- AI 결과를 바로 확정하지 않고, 사용자가 근거를 확인하고 판단할 수 있게 합니다.
- 기능을 화면에서 끝내지 않고 API, 데이터 저장, 권한, 운영 흐름까지 연결합니다.
- 실패와 진행 상태를 드러내고, 재시도와 검증이 가능한 구조를 만듭니다.
- 운영 비밀 정보와 사용자 데이터를 코드 및 배포 설정과 분리합니다.

---

## GitHub

프로젝트의 코드와 실행·설계 내용은 각 저장소 README에서 확인할 수 있습니다.

- [Hub](https://github.com/chl4890620123-collab/hub)
- [AITM](https://github.com/chl4890620123-collab/Aitm)
- [Restok](https://github.com/chl4890620123-collab/Restok-Rangchain)
- [Maple Craft Analytics](https://github.com/chl4890620123-collab/maple)
- [Server Infrastructure](https://github.com/chl4890620123-collab/Server)
