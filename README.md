<div align="center">

# Kim Jiyoun

### AI Software Developer · Product Builder · Project Manager

**문제를 발견하고, 기술로 해결책을 설계하고, 실제 서비스까지 구현합니다.**

AI · Computer Vision · Web · Embedded System을 활용하여
아이디어를 실제 동작하는 제품과 서비스로 만드는 프로젝트를 진행하고 있습니다.

</div>

---

## 👋 About Me

동양미래대학교 **인공지능소프트웨어학과**에서 공부하고 있습니다.

단순히 주어진 기능을 개발하는 것보다,

**Problem → Planning → Development → Validation → Improvement**

의 전체 과정을 경험하며 실제 사용자의 문제를 해결하는 프로젝트를 만드는 것을 좋아합니다.

특히 AI 기술을 서비스에 적용하는 과정과
소프트웨어·하드웨어·UX를 하나의 제품으로 통합하는 프로젝트에 관심이 있습니다.

---

# 🚀 Featured Projects

## 🪞 Mirror-Ting

### Smart Mirror-based Workplace Dialogue Training System

> **AI 기반 스마트미러 직장생활 시뮬레이션 & 코칭 시스템**

취업 준비생과 사회초년생이 실제 직장에서 경험할 수 있는 상황을
AI와의 역할극을 통해 반복적으로 연습할 수 있도록 설계한 프로젝트입니다.

업무 보고, 실수 설명, 예상하지 못한 질문, 피드백 대응 등
현실적인 직장 상황을 AI가 재현하고 사용자의 **답변·음성·표정·자세**를 종합적으로 분석합니다.

### Problem

기존 취업 교육은 면접 준비에 집중되어 있어
실제 입사 이후 필요한 직장 커뮤니케이션을 연습할 수 있는 환경이 부족합니다.

### Solution

스마트미러 환경에서 AI 캐릭터와 실제 대화를 진행하고
대화 과정의 언어적·비언어적 행동을 분석하여 개인화된 피드백을 제공합니다.

### Core Features

* LLM 기반 직장 상황 Role-Play
* STT 기반 음성 대화 처리
* AI 기반 답변 분석
* Computer Vision 기반 표정 분석
* Computer Vision 기반 자세 분석
* Voice / Response / Expression / Posture 분석
* 세션별 피드백 리포트
* Smart Mirror 기반 자기관찰 UX
* NFC 기반 사용자 경험 연동

### My Contribution

`Project Manager` `Hardware Lead` `System Planning`

* 프로젝트 아이디어 및 전체 서비스 구조 기획
* 사용자 경험 및 시나리오 설계
* AI 시스템 아키텍처 설계
* Frontend · Backend · AI 간 기능 요구사항 정의
* 스마트미러 및 사원증 키오스크 하드웨어 설계
* 팀 역할 및 개발 일정 관리
* 프로젝트 발표 및 문서화

### Tech

`React` `Vite` `Python` `Computer Vision` `LLM`
`STT` `NFC` `Smart Mirror` `Web API`

---

## 🧠 Ginger

### AI-based Korean Descriptive Answer Analysis

> **한국어 서술형 답변을 분석하여 사고 수준을 분류하고 피드백하는 AI 서비스**

사용자가 작성한 한국어 서술형 답변을 머신러닝으로 분석하여
사고 수준을 단계별로 분류하고 결과에 따라 추가 질문과 피드백을 제공하는 프로젝트입니다.

### Problem

객관식 평가만으로는 사용자가
어떤 수준까지 내용을 이해하고 사고하고 있는지 판단하기 어렵습니다.

### Solution

한국어 서술형 데이터를 TF-IDF로 벡터화하고
여러 머신러닝 분류 모델을 비교하여 사용자의 사고 수준을 예측하도록 구현했습니다.

### ML Pipeline

```text
User Answer
     ↓
Text Preprocessing
     ↓
TF-IDF Vectorization
     ↓
Machine Learning Model
     ↓
Thinking Level Classification
     ↓
Confidence Analysis
     ↓
Feedback / Follow-up Question
```

### Models

* Logistic Regression
* Support Vector Machine
* Decision Tree
* Random Forest

### Evaluation

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

### Key Feature

예측 신뢰도가 낮은 답변의 경우
단순 결과 출력 대신 추가 질문을 제공하여 사용자의 사고를 다시 확인하도록 설계했습니다.

### Tech

`Python` `scikit-learn` `TF-IDF`
`Pandas` `NumPy` `Machine Learning`

---

## 🗣 RISE

### Voice-based Accessible Kiosk

> **고령층의 디지털 접근성을 위한 음성 기반 주문 키오스크**

기존 터치스크린 중심 키오스크 사용에 어려움을 겪는 고령층을 위해
음성 인터페이스를 활용한 주문 시스템을 제작한 프로젝트입니다.

### Problem

기존 키오스크는 작은 글씨, 복잡한 메뉴 구조와
터치 중심 인터페이스로 인해 디지털 취약계층에게 높은 사용 장벽을 제공합니다.

### Solution

사용자가 화면을 여러 번 탐색하지 않아도
음성으로 원하는 메뉴를 말하고 주문을 진행할 수 있도록 인터페이스를 설계했습니다.

### Core Features

* Voice-based Menu Selection
* Touch + Voice Hybrid Interface
* 사용자 중심 주문 프로세스
* Raspberry Pi 기반 키오스크
* Touch Display 연동
* Web UI 기반 화면 구성

### Hardware

```text
Raspberry Pi 5
     +
10.1" Touch Display
     +
Microphone / Speaker
     +
Web Application
```

### My Contribution

* 서비스 아이디어 및 UX 기획
* 키오스크 사용자 플로우 설계
* Raspberry Pi 하드웨어 구성
* 터치 디스플레이 환경 구축
* 음성 인터페이스 기획
* 시제품 통합 및 테스트

### Tech

`Raspberry Pi` `Python` `Web`
`Voice Interface` `Touch Display`

---

# 🧩 What I Build

저는 특정 기술 하나에 프로젝트를 맞추기보다
**문제를 해결하기 위해 필요한 기술을 조합하는 방식**으로 개발합니다.

```text
          Problem
             │
             ▼
      Service Planning
             │
             ▼
     System Architecture
        ┌────┴────┐
        ▼         ▼
       AI       Software
        │         │
        └────┬────┘
             ▼
          Hardware
             │
             ▼
           Product
```

### AI

`Machine Learning` `Computer Vision` `LLM`
`STT` `Data Analysis`

### Software

`Python` `Java` `JavaScript`
`React` `Vite` `HTML` `CSS`

### Hardware / Embedded

`Raspberry Pi` `NFC` `Sensors`
`Touch Display` `Smart Mirror`

### Product

`Project Management` `Service Planning`
`UX Design` `System Architecture` `Prototyping`

---

# 🏆 Awards & Achievements

### 2026

* 🏆 **동양미래대학교 EXPO 본선 진출**

* 🚀 **미래여성경제인육성사업 실전창업멘토링 및 IP 권리화 프로그램 본선 진출**

* 🥈 **학생참여형 리빙랩 활동 지원 프로그램 우수상**

* 🥈 **태일씨앤티 웹사이트 리뉴얼 경진대회 우수상**

* 🚀 **도전! 메가시티 리그전 본선 진출**

* 🚀 **D.StartupZone 입주 학생 선발**

### 2025

* 🥉 **한국실천공학회 교육장비개발대회 동상**

* 🥉 **AI로 만드는 우리 대학 이야기 공모전 동상**

---

# 🛠 Tech Stack

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square\&logo=openjdk\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square\&logo=css3\&logoColor=white)

### AI / Data

![Scikit Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square\&logo=scikitlearn\&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square\&logo=opencv\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square\&logo=numpy\&logoColor=white)

### Frontend / Tools

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square\&logo=react\&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square\&logo=vite\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square\&logo=github\&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square\&logo=figma\&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square\&logo=raspberrypi\&logoColor=white)

---

# 📊 GitHub

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=sdg331\&show_icons=true\&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sdg331\&layout=compact\&hide_border=true)

</div>

---

# 🎯 Currently Interested In

```text
AI-powered Products
Computer Vision
Human-AI Interaction
Embedded Systems
AI Service Development
Product Management
Startup & Prototyping
```

---

# 📫 Contact

**GitHub**
https://github.com/sdg331

---

<div align="center">

### From Problem to Product.

**Discover → Design → Develop → Validate**

</div>
