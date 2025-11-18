<div align='center'>
<h1>🌟 silence102 포트폴리오</h1>
<h3>AI 엔지니어</h3>
<p><i>“Python, JavaScript, Java를 주로 사용하며 백엔드 개발과 AI/ML 모델 구현, 프론트엔드 연동을 병행하는 AI 엔지니어입니다. GitHub에서 여러 저장소를 활발히 관리하며 API 설계와 모델 성능 개선, 프론트엔드 통합 작업 중심의 실용적인 코드를 제공합니다. 문서화와 재현 가능한 실험 환경을 중시하여 협업과 유지보수에 강점을 보입니다.”</i></p>
</div>

---

## 📑 목차

- [🛠 기술 스택 개요](#-기술-스택-개요)
- [🚀 대표 프로젝트](#-대표-프로젝트)
- [⚙️ 트러블슈팅 사례](#️-트러블슈팅-사례)
- [📚 학습 및 성장](#-학습-및-성장)
- [📄 Footer](#footer)

---

## 🎨 Skill Icons

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="50" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="50" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="50" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="50" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" width="50" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="50" />
</p>


---

## 🛠 기술 스택 개요

| 분야 | 기술 | 숙련도 | 사용 빈도 | 경험 연차 | 자신도 | 설명 |
|------|------|---------|------------|-------------|----------|-------|
| **language** | Python | ⭐⭐⭐⭐⭐ | daily | 2.02년 | high | Python으로 데이터 수집·정제와 반복 작업 자동화를 구현하고, Flask 기반의 간단한 API로 백엔드 프로토타입을 만들었습니다. |
| **language** | Java | ⭐⭐⭐⭐☆ | daily | 0.22년 | high | Java로 Spring Boot 기반의 RESTful 마이크로서비스와 배치 데이터 처리 로직을 구현하고 운영해 왔습니다. JPA/JDBC를 이용한 DB 연동, 멀티스레딩 처리 및 JUnit을 활용한 단위·통합 테스트 작성에 익숙합니다. |
| **language** | Javascript | ⭐⭐⭐⭐☆ | daily | 0.96년 | high | 브라우저 기반 인터랙티브 UI와 RESTful API 연동을 위해 ES6+ 문법과 모듈화를 사용해 DOM 조작, 이벤트 처리 및 비동기 요청을 구현했습니다. |
| **framework** | FastAPI | ⭐⭐⭐☆☆ | weekly | 2.1년 | medium | FastAPI로 비동기 REST API를 설계·구현하여 프론트엔드와 내부 마이크로서비스 간 통신을 처리했습니다. Pydantic 기반 입력 검증과 자동 생성되는 OpenAPI 문서로 API 계약을 명확히하고 유지보수를 쉽게 했습니다. |
| **framework** | Spring Boot | ⭐⭐⭐☆☆ | weekly | 2.1년 | medium | Spring Boot로 RESTful API 기반 백엔드와 마이크로서비스를 구현하고 Spring Data JPA와 Spring Security로 데이터 접근과 인증을 관리했습니다. 자동 설정과 프로파일을 이용해 로컬·운영 환경을 분리하고 컨테이너로 배포했습니다. |
| **framework** | React | ⭐⭐⭐☆☆ | weekly | 2.1년 | medium | React로 컴포넌트 기반의 재사용 가능한 UI를 설계하고 구현했습니다. Hooks와 라우터를 활용해 사용자 상호작용이 많은 SPA를 안정적으로 개발한 경험이 있습니다. |
| **devops** | Jenkins | ⭐⭐⭐☆☆ | weekly | 2.1년 | medium | Jenkins를 사용해 GitHub PR 병합 시 자동 빌드·단위테스트를 실행하고 Docker 이미지 빌드 후 스테이징 환경으로 배포하는 CI/CD 파이프라인을 구축했습니다. Jenkinsfile과 플러그인으로 파이프라인을 코드화하고 알림·아티팩트 관리를 통합해 배포 반복 작업을 줄였습니다. |

---

## 🚀 대표 프로젝트


<div align="center">

### 🧭 Algorithm-Study

> A personal repository documenting algorithm problem solving on Baekjoon and Programmers. Contains Python solutions and notes (Markdown) covering problems from Bronze to Gold level. Active practice with 100 commits over 186 days, focused on coding challenges and algorithmic learning.

📅 <b>기간:</b> 2023-07-25 ~ 2025-08-29  
👥 <b>팀 구성:</b> 1명  
💼 <b>담당 역할:</b> ai  

</div>

### 💪 주요 기여
- **기여율:** 100%

### 🧠 주요 책임
- Implement algorithmic solutions in Python for problems on Baekjoon and Programmers
- Organize solutions and reference notes into platform folders and maintain README documentation
- Iteratively improve implementations based on runtime/memory characteristics reported by the judge

### ⚙️ 트러블슈팅 사례


<details>
<summary><b>🔧 Performance and memory bottlenecks on higher-difficulty (Gold) problems</b></summary>

**분석:** Some Gold-level submissions showed high execution time and memory usage (commit messages include measured runtimes and memory). Causes included algorithmic complexity for large inputs and non-optimal data handling in Python.  
**해결:** Profile and refine approaches: choose asymptotically better algorithms (BFS/DFS optimizations, more efficient graph traversals, pruning), adopt Python performance patterns (use deque for queues, avoid unnecessary copies, faster I/O where appropriate), and iteratively submit tuned versions to the judge.  
**결과:** Solutions accepted on the online judge (commit messages reference Baekjoon submissions). Multiple attempts and commits for the same problems reflect iterative tuning informed by measured runtimes and memory footprints.

</details>


---


<div align="center">

### 🧭 DATAEDU_2M — 멀티 비전 모델 예제 및 레이블링 연계 저장소

> Python 기반으로 여러 비전 관련 모델 예제(YOLOv5, SAM, BLIP, EasyOCR 등)를 한곳에 모아둔 실습/연구용 저장소입니다. 레이블링 예제(label-studio 관련 파일)와 간단한 테스트 코드, 모델 파일(.pth 등)을 포함하고 있으며 README로 사용법과 구성 안내를 제공하고 있습니다. 기여는 AI 모델 구성과 예제 제공에 초점이 맞춰져 있습니다.

📅 <b>기간:</b> 2023-07-04 ~ 2023-07-04  
👥 <b>팀 구성:</b> 1명  
💼 <b>담당 역할:</b> ai  

</div>

### 💪 주요 기여
- **기여율:** 100%

### 🧠 주요 책임
- AI 모델 예제 코드 작성 및 리포지토리 정리(주요 AI 디렉토리 구성 및 파일 추가)
- 레이블링 워크플로우 연동을 위한 Label Studio 예제 파일 제공
- 기본 문서화(README)를 통해 사용 방법과 데이터/모델 취급 지침 요약
- 간단한 테스트 코드로 모델 동작 검증 보조

### ⚙️ 트러블슈팅 사례


<details>
<summary><b>🔧 여러 타입의 모델(탐지, 세분화, OCR, 비전-언어)이 한 저장소에 모여 있어 초기 구조 파악이 어려움</b></summary>

**분석:** 디렉토리별로 모델 코드와 다양한 파일 형식(.py, .pth, .json 등)이 섞여 있으며 커밋 수가 적어 사용 흐름이 즉시 명확하지 않을 수 있음  
**해결:** 모델별로 디렉토리를 명확히 구분하고 README에 각 디렉토리의 목적과 간단 사용 예시를 작성함(이미 README 생성 및 주요 디렉토리 존재).  
**결과:** 후속 사용자가 모델의 위치와 예제 파일을 빠르게 파악할 수 있게 되었고, 재현성을 위한 기본 안내가 마련됨.

</details>


<details>
<summary><b>🔧 환경 및 의존성 재현(실행 환경 차이) 관련 고려가 필요함</b></summary>

**분석:** README에 'docker' 키워드가 등장하지만 커밋 내에서 의존성 설치 스크립트나 완전한 컨테이너 설정이 명시적으로 추가되지는 않음  
**해결:** README에서 권장 파이썬 버전, 주요 라이브러리(예: YOLOv5 요구사항, EasyOCR 등) 및 Label Studio 사용 시 참고할 점을 명시하여 환경 준비를 돕도록 문서화함.  
**결과:** 직접적인 컨테이너 제공 없이도 사용자가 필요한 의존성을 빠르게 확인하고 환경을 마련할 수 있도록 안내가 개선됨(추가로 도커 파일 등은 후속 보완 가능).

</details>


---


<div align="center">

### 🧭 Storage-Locker-Project — Arduino 기반 물품 보관함 (Python 백엔드 / JS 프론트엔드)

> 아두이노(ino) 하드웨어 스케치와 Python 기반 서버 연동을 목표로 한 물품 보관함 프로젝트입니다. 레포지토리에는 Python(69%)과 JavaScript(31%) 코드가 주를 이루며, 회원가입·로그인 관련 API와 입력 검증(validation) 관련 커밋, ERD 설계 파일, 프론트엔드 템플릿/JS 코드가 존재합니다. 총 27회 커밋으로 약 58일에 걸쳐 작업한 이력이 있습니다.

📅 <b>기간:</b> 2024-03-03 ~ 2024-05-29  
👥 <b>팀 구성:</b> 1명  
💼 <b>담당 역할:</b> ai  

</div>

### 💪 주요 기여
- **기여율:** 100%

### 🧠 주요 책임
- Python 코드 중심으로 서비스 로직 및 입력 검증 관련 구현/수정
- 프론트엔드(JavaScript, HTML)에서의 서버 연동 시도 및 클라이언트 로직 작업
- ERD 문서화로 데이터 구조 설계에 기여
- 레포지토리 정리 및 Git 사용(파일 삭제/추가/업로드 등)으로 코드베이스 유지관리

### ⚙️ 트러블슈팅 사례


<details>
<summary><b>🔧 프론트엔드와 백엔드 간 서버 연동 불안정 (여러 차례 '서버 연동 시도' 커밋 존재)</b></summary>

**분석:** 커밋 메시지에 '서버 연동 시도...'가 반복되어 있으며, 프론트엔드 쪽 JS와 템플릿 파일이 함께 존재함. 이는 클라이언트-서버 인터페이스(엔드포인트, 요청/응답 형식) 조율이 진행 중이었음을 시사함.  
**해결:** 프론트엔드 JS와 서버의 API 엔드포인트(회원가입/로그인/validation)를 반복적으로 수정·테스트하여 요청 형식을 맞추는 작업을 수행함.  
**결과:** 여러 차례의 수정 커밋을 통해 연동 시도를 지속했으며, 관련 API 구현 커밋이 남아 있어 인터페이스 정합성 확보를 위한 진행이 이루어짐(완전한 통합 여부는 레포지토리만으로 확정 불가).

</details>


<details>
<summary><b>🔧 중복되거나 불필요해 보이는 파일(예: validation.py, app.py)의 삭제와 리팩터링 이력</b></summary>

**분석:** 'Delete validation.py', 'Delete app.py' 등의 커밋이 존재하여 초기 구현을 정리하거나 구조를 변경하는 과정이 있었음을 보여줌.  
**해결:** 문제의 원인이 된 파일들을 삭제하고 템플릿/새로운 구현으로 대체하거나 검증 로직을 재구성하는 방식으로 리팩터링을 진행함.  
**결과:** 레포지토리 정리가 이루어지고 코드베이스가 재구성된 흔적이 남아 있어 향후 유지보수 및 추가 개발을 위한 기반이 정리됨.

</details>


---

<div id='footer' align='center'>
Generated by **COditor – AI Developer Archive System**<br>
🕒 마지막 업데이트: 2025-11-18
</div>