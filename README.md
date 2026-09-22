<div align="center">

# 김지연 · Kim Jiyeon

### AI Software Developer · AI Engineer in Progress

**인공지능을 이해하는 것에서 끝나지 않고, 실제로 동작하는 시스템으로 구현합니다.**

데이터와 모델을 이해하고,
AI · Web · Embedded 기술을 연결해
사용자가 직접 경험할 수 있는 제품을 만드는 개발자를 목표로 하고 있습니다.

[Projects](#featured-projects) · [AI Focus](#ai-engineering-focus) · [Skills](#technical-skills) · [Awards](#awards)

</div>

---

## About Me

동양미래대학교 **인공지능소프트웨어학과**에서 AI와 소프트웨어 개발을 공부하고 있습니다.

단순히 AI API를 사용하는 개발자가 아니라,

**문제 정의 → 데이터와 AI 방법 선택 → 모델 및 시스템 구현 → 평가 → 실제 제품 적용**

전체 과정을 이해하고 수행할 수 있는 AI 엔지니어로 성장하는 것이 목표입니다.

현재는 머신러닝, 자연어 처리, Computer Vision, LLM 기반 서비스를 중심으로 공부하면서
웹 애플리케이션과 Raspberry Pi, NFC, 센서 등의 하드웨어를 연결해 실제 환경에서 사용할 수 있는 시스템을 만들고 있습니다.

제가 중요하게 생각하는 것은 기술 자체보다
**“이 AI가 실제 문제를 해결할 수 있는가?”** 입니다.

---

## AI Engineering Focus

현재 다음 영역을 중심으로 AI 전문성을 확장하고 있습니다.

### Machine Learning

* `scikit-learn` 기반 머신러닝 파이프라인
* 데이터 전처리 및 특징 추출
* 텍스트 분류
* TF-IDF 기반 자연어 처리
* 모델 예측 결과와 신뢰도 처리

### Generative AI · LLM

* LLM 기반 대화형 서비스
* 사용자 입력에 따른 AI 응답 흐름 설계
* AI 서비스와 백엔드 시스템 연동
* STT와 LLM을 연결한 음성 기반 인터랙션
* 생성형 AI를 실제 제품 경험으로 연결하는 방법 탐구

### Computer Vision

* 카메라 기반 사용자 인식
* 영상 입력을 활용한 인터랙티브 시스템
* Computer Vision과 웹 서비스의 연동
* 실제 공간에서 동작하는 AI 인터페이스 구현

### AI Product Engineering

AI 모델만 만드는 것이 아니라,

```text
User
 ↓
Interface
 ↓
AI / ML
 ↓
Backend
 ↓
Data
 ↓
Hardware / External System
```

전체 시스템이 연결되어 동작하는 구조를 만드는 것에 관심이 있습니다.

---

## Technical Skills

| Area                      | Technologies                                                         |
| ------------------------- | -------------------------------------------------------------------- |
| **AI · Machine Learning** | `scikit-learn` `TF-IDF` `Computer Vision` `LLM` `STT`                |
| **Data**                  | `Pandas` `NumPy` `SQLite`                                            |
| **Languages**             | `Python` `Java` `JavaScript` `HTML` `CSS`                            |
| **Frontend**              | `React` `Vite` `Streamlit`                                           |
| **Backend**               | `FastAPI` `REST API`                                                 |
| **Embedded · IoT**        | `Raspberry Pi` `NFC` `Sensors` `Touch Display`                       |
| **Engineering**           | `Git` `GitHub Actions` `pytest` `Docker`                             |
| **System Design**         | `AI Service Architecture` `Hardware Integration` `Rapid Prototyping` |

---

# Featured Projects

## Mirror-Ting

### AI 기반 거울형 직장 대화 훈련 시스템

> 실제 직장에서 발생할 수 있는 보고, 질문, 피드백 상황을 AI와 연습하고 자신의 커뮤니케이션을 확인하는 스마트미러 기반 서비스

**Role**
`Project Manager` `System Planning` `Hardware Lead`

**AI & System**

* 음성 기반 사용자 인터랙션 흐름 설계
* STT와 LLM을 활용한 대화형 역할극 시스템 구성
* Computer Vision 기반 사용자 인터랙션 구조 설계
* 사용자 행동과 대화 결과를 연결하는 피드백 경험 설계
* AI · Frontend · Backend 사이의 세션 및 데이터 흐름 정의

**Hardware**

* 65인치 스마트미러 시스템
* Azure Kinect 기반 사용자 인식
* NFC 사원증 연동
* Raspberry Pi 기반 사원증 발급 키오스크
* 기관 관리자용 분석 대시보드

`React` `Vite` `FastAPI` `Computer Vision` `LLM` `STT` `NFC` `Raspberry Pi`

---

## [Ginger](https://github.com/sdg331/ginger-app)

### 학습자의 생각을 확장하는 AI 질문 코치

> 정답을 바로 제공하기보다 사용자의 답변을 분석하고 다음 사고 단계로 이어지는 질문을 제공하는 학습 서비스

**AI Focus**

* 한국어 서술형 답변을 TF-IDF 특징으로 변환
* `scikit-learn` 기반 분류 모델 구축
* 답변 특징을 Level 1~4 형태로 분석
* 예측 신뢰도가 낮은 상황을 위한 fallback 처리
* 모델 추론 과정과 사용자 인터페이스 분리

**Engineering**

* Streamlit 기반 인터페이스
* AI 추론 모듈 구조화
* 테스트 코드 작성
* Docker 실행 환경 구성
* GitHub Actions 기반 CI 구성

`Python` `scikit-learn` `TF-IDF` `Streamlit` `Docker` `GitHub Actions`

---

## [Neuro Drive](https://github.com/sdg331/neuro-drive)

### 강화학습 과정을 직접 관찰하는 AI 리터러시 게임

> AI가 학습하고 실패하고 전략을 바꾸는 과정을 사용자가 직접 실험할 수 있도록 만든 브라우저 기반 교육 프로젝트

**AI Focus**

외부 머신러닝 라이브러리를 사용하지 않고 JavaScript로 직접 구현했습니다.

* Deep Q-Network 구조
* Neural Network
* Forward Propagation
* Backpropagation
* Experience Replay
* Target Network
* Reward 기반 학습 과정

학습 결과를 단순 점수로 보여주는 대신,

* Learning Curve
* Value Map
* Neural Network State
* Reward Hacking Experiment

등을 시각화해 AI의 학습 과정을 관찰할 수 있도록 설계했습니다.

`JavaScript` `HTML` `CSS` `Canvas` `DQN` `PWA`

[Live Demo](https://sdg331.github.io/neuro-drive/) · [Source Code](https://github.com/sdg331/neuro-drive)

---

## [ReliefCheck](https://github.com/sdg331/CarpeDM_EswContest)

### 네트워크 없이 동작하는 구호물자 지급 관리 시스템

> 인터넷 연결이 불안정한 재난 현장에서도 중복 지급을 방지하고 지급 기록을 관리할 수 있는 Raspberry Pi 기반 시스템

**System Engineering**

* 듀얼 NFC 입력
* 지급 정책 판정
* 재고 관리
* SQLite 기반 감사 원장
* 영수증 출력
* 카메라 및 하드웨어 연동

거래 상태와 프린터 출력 상태를 분리하여
출력 오류가 실제 거래 중복으로 이어지지 않도록 시스템을 설계했습니다.

NFC · Printer · Camera 등의 장치를 어댑터 구조로 분리하고
단위 테스트와 검증 리포트 생성 흐름을 구현했습니다.

`Python` `SQLite` `Raspberry Pi` `NFC` `JavaScript` `pytest`

---

## More Projects

### [헛똑똑이 랩](https://github.com/sdg331/heotlab)

AI의 **Hallucination**과 **Reward Hacking**을 짧은 실험으로 경험할 수 있도록 만든 AI 리터러시 웹 애플리케이션

[Live Demo](https://sdg331.github.io/heotlab/)

### [AI Indie Game Hackathon](https://github.com/sdg331/AI_INDIGAME_HACKATHON)

Unity 기반 AI 인디게임 해커톤 프로젝트

---

# How I Approach AI

AI를 사용할 때 다음 과정을 중요하게 생각합니다.

```text
1. Define the Problem
        ↓
2. Understand the Data
        ↓
3. Choose the AI Approach
        ↓
4. Build a Baseline
        ↓
5. Implement the System
        ↓
6. Evaluate the Result
        ↓
7. Integrate with the Product
        ↓
8. Improve
```

AI 모델의 성능만 보는 것이 아니라
사용자가 실제로 사용할 수 있는 전체 시스템을 만드는 것을 목표로 합니다.

---

# Currently Learning

현재 다음 주제를 더 깊게 공부하고 있습니다.

* Machine Learning fundamentals
* Deep Learning
* Natural Language Processing
* Computer Vision
* LLM-based Applications
* AI Model Evaluation
* AI System Architecture
* AI Deployment & MLOps

장기적으로는 특정 AI 도구에 의존하는 것이 아니라
새로운 문제를 만났을 때 적절한 모델과 기술을 선택하고 직접 검증할 수 있는
**AI Engineer**가 되는 것이 목표입니다.

---

# Awards

| Year | Award | Program · Competition |
| ---- | ----- | --------------------- |
| 2026 | 우수상   | 학생참여형 리빙랩 활동 지원 프로그램  |
| 2026 | 우수상   | 태일씨앤티 웹사이트 리뉴얼 경진대회   |
| 2025 | 동상    | 한국실천공학회 교육장비개발대회      |
| 2025 | 동상    | AI로 만드는 우리 대학 이야기 공모전 |

## Activities

| Year | Result | Program                           |
| ---- | ------ | --------------------------------- |
| 2026 | 본선 진출  | 동양미래대학교 EXPO                      |
| 2026 | 본선 진출  | 미래여성경제인육성사업 실전창업멘토링 및 IP 권리화 프로그램 |
| 2026 | 본선 진출  | 도전! 메가시티 리그전                      |
| 2026 | 선발     | D.StartupZone 입주 학생               |
| 2026 | 참여     | AI Indie Game Hackathon           |

---

## Contact

**GitHub**
[github.com/sdg331](https://github.com/sdg331)

---

<div align="center">

### From AI Models to Real-World Systems

**Learn · Build · Evaluate · Improve**

</div>
