<div align="center">

<img src="./assets/profile-hero-v2.svg" width="100%" alt="Jiyeon Kim — AI Software, Product Engineering, Human-AI Experience" />

<br/>

### AI를 모델에서 끝내지 않고, 사용자가 직접 경험하는 제품과 시스템까지 연결합니다.

`AI Software` · `Product Engineering` · `Web` · `Embedded` · `Human-AI Experience`

<br/>

<a href="#selected-work">Selected Work</a> ·
<a href="#toolkit">Toolkit</a> ·
<a href="#currently">Currently</a> ·
<a href="#highlights">Highlights</a>

</div>

---

## Hello, I'm Jiyeon.

동양미래대학교 **인공지능소프트웨어학과**에서 AI와 소프트웨어를 공부하고 있는 김지연입니다.

**문제 정의부터 AI·웹·하드웨어의 연결, 테스트와 운영 흐름까지** 살피며 실제로 사용할 수 있는 시스템을 만드는 데 관심이 있습니다. 특히 대화형 AI, 컴퓨터비전, 학습을 돕는 인터랙션을 탐구하고 있습니다.

- **AI applications** — 모델과 LLM을 사용자의 입력·응답·피드백 흐름에 연결합니다.
- **End-to-end systems** — 프런트엔드, API, 데이터와 장치 사이의 계약을 설계합니다.
- **Reliable experiences** — 정상 동작뿐 아니라 오류·재시도·복구와 구현의 한계도 확인합니다.

> **Problem → Prototype → Evaluate → Integrate → Improve**

---

# Selected Work

## 01. 4-Fit MirrorTing
### AI Workplace Communication · Team CarpeDM

**업무 대화를 AI 역할극으로 연습하고, 응답·목소리·표정·자세의 4-Fit 관점에서 돌아보는 전시용 스마트미러 프로젝트**

`Project Manager` `System Planning` `Hardware Integration`

팀 프로젝트에서 체험 흐름과 시스템 기획, 하드웨어 연결을 중심으로 참여했습니다.

- React/Vite 화면과 FastAPI 기반 대화·분석·리포트 구조
- Chrome STT, 녹음 후 Whisper 분석, LLM 대화와 음성 응답 연결
- NFC 방문자 연결과 스마트미러·키오스크 사이의 세션 흐름 설계

현재 스마트미러 체험은 **한 가지 직장 상황의 3턴 대화**입니다. 화면 미리보기, 실제 AI 실행, 실물 장치 연동을 구분하며 분석 결과는 참고용으로 다룹니다.

[Core Repository](https://github.com/DMUCarpeDM/2026CarpeDM_EXPO) ·
[Project Website](https://sdg331.github.io/CarpeDM_EXPO_Microsite/) ·
[Microsite Source](https://github.com/sdg331/CarpeDM_EXPO_Microsite) ·
[Sample Dashboard](https://github.com/sdg331/CarpeDM_EXPO_dashboard)

`React` `TypeScript` `FastAPI` `STT / TTS` `LLM` `Computer Vision`

## 02. MirrorTing ID Printer
### Face · NFC · Thermal Printing

**얼굴 촬영과 캐릭터 매칭, NFC 카드 연결, 사원증·체험 리포트 출력으로 이어지는 CarpeDM 체험 키오스크**

- YuNet/SFace 기반 로컬 얼굴 처리와 8개 캐릭터 매칭
- FastAPI·SQLite 기반 방문자 세션, NFC 연결, 출력 작업 상태 관리
- 출력 작업 중복 방지와 결과가 불확실한 작업의 운영자 복구 흐름

샘플 화면과 실제 장치 실행을 분리했습니다. 소프트웨어 테스트와 별개로 카메라·NFC·감열 프린터의 실물 검증이 필요합니다.

[Repository](https://github.com/sdg331/CarpeDM_EXPO_IDPrinter) ·
[Implementation & Operations](https://github.com/sdg331/CarpeDM_EXPO_IDPrinter/blob/main/docs/OPERATIONS.md)

`JavaScript` `FastAPI` `SQLite` `YuNet / SFace` `NFC` `Raspberry Pi`

## 03. 생강 · Ginger
### Question-based Thinking Coach

**사용자의 답변을 바탕으로 후속 질문을 제안하고, 스스로 고쳐 쓰며 생각을 발전시키도록 돕는 초기 MVP**

- TF-IDF·scikit-learn 기반 답변 특징 분석과 낮은 확신도에 대한 fallback
- 질문을 반영하는 라운드형 사고 훈련과 수정 전후 답변 비교
- 선택형 LLM 판단·질문 생성 계층, pytest·Docker·GitHub Actions 구성

모델의 Level은 사람의 사고력을 확정하는 점수가 아닙니다. **템플릿 데이터 내부 성능과 분포 밖 평가를 구분**하며, 실제 학습 효과는 별도의 검증 과제입니다.

[Repository](https://github.com/sdg331/ginger-app) ·
[Limitations & Evaluation](https://github.com/sdg331/ginger-app/blob/main/reports/limitations_and_adversarial_findings.md)

`Python` `Streamlit` `scikit-learn` `TF-IDF` `LLM` `pytest`

## 04. 틈길 · TEUMGIL
### Market Discovery & Community Workflow · 길이음팀

**전통시장 점포·품목 탐색과 장보기, 시민·운영자·상인의 의견 처리 흐름을 연결하는 웹앱 MVP**

- Next.js·TypeScript와 PostgreSQL 기반 가입·로그인·DB 세션
- 시장·점포 검색, 계정별 장보기 목록, 의견 작성과 초안 복구
- 운영자 확인·전달·게시와 상인 답변을 분리한 역할별 접근·감사 기록

현재는 **가상 자료로 체험하는 MVP**입니다. 실제 지도·AI·메일은 미연동이며, 앱 내부 의견 접수는 공식 민원 접수와 다릅니다.

[Repository](https://github.com/sdg331/Teumgil) ·
[Architecture](https://github.com/sdg331/Teumgil/blob/main/docs/ARCHITECTURE.md) ·
[Verification Scope](https://github.com/sdg331/Teumgil/blob/main/docs/MVP_VERIFICATION.md)

`Next.js` `TypeScript` `PostgreSQL` `PGlite` `Playwright`

## 05. 근거노트
### Evidence-linked Korean Document Q&A

**문서에 질문하고, 답변의 근거·쪽수·발췌 내용을 직접 확인하는 한국어 문서 질의응답 데모**

- React·FastAPI·SQLite 기반 문서 업로드와 검색
- 근거가 부족한 질문의 답변 보류, 선택형 Ollama 의미 검색·AI 답변
- 읽기 전용 공개 시연 모드와 재현 가능한 작은 검색 평가 세트

샘플 문서 기반 데모이며, 인용 표시만으로 답변의 사실성을 보증하지 않습니다.

[Repository](https://github.com/sdg331/evidence-note)

`React` `TypeScript` `FastAPI` `SQLite` `Ollama` `pytest`

## 06. ReliefCheck
### Offline-first Relief Distribution · Team Project

**재난 대피소에서 지급 기준과 거래 기록을 확인하는 Raspberry Pi 기반 오프라인 우선 구호물자 지급 단말**

- 가구 카드·물품 태그를 구분하는 듀얼 NFC 흐름과 정책 엔진
- SQLite 원장에 거래를 먼저 기록하고 출력 상태를 별도로 관리
- 장치 어댑터, 오류·중복 지급 방지 테스트와 소프트웨어 검증 리포트

정책·거래 기록 검증과 실제 장치의 반복 인식·출력 성능 측정을 구분합니다.

[Repository](https://github.com/sdg331/CarpeDM_EswContest)

`Python` `SQLite` `JavaScript` `Raspberry Pi` `NFC` `pytest`

---

### More Experiments

**[Neuro Drive](https://github.com/sdg331/neuro-drive)** · [Live Demo](https://sdg331.github.io/neuro-drive/)  
순수 JavaScript 기반 DQN 레이싱 실험실. 학습 곡선·가치 지도·신경망 상태와 보상 설계 실험을 통해 강화학습 과정을 관찰합니다.

**[헛똑똑이 랩](https://github.com/sdg331/heotlab)** · [Live Demo](https://sdg331.github.io/heotlab/)  
환각과 보상 해킹을 체험하는 AI 리터러시 웹앱. 실패 사례는 사전 작성된 시뮬레이션이며 라이브 LLM 호출은 사용하지 않습니다.

**[AI Indie Game Hackathon](https://github.com/sdg331/AI_INDIGAME_HACKATHON)**  
Unity·C# 기반 팀 게임 프로젝트. 플레이어 액션과 보스 패턴을 구현합니다.

---

# Toolkit

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,js,ts,react,nextjs,fastapi,postgres,sqlite,docker,git,raspberrypi,figma&perline=12" alt="Python, JavaScript, TypeScript, React, Next.js, FastAPI, PostgreSQL, SQLite, Docker, Git, Raspberry Pi, Figma" />
</div>

<br/>

| Area | Working With |
| --- | --- |
| **AI · ML** | scikit-learn · TF-IDF · LLM Applications · STT / TTS · Computer Vision |
| **Frontend** | React · Next.js · TypeScript · JavaScript · Vite · Streamlit |
| **Backend · Data** | Python · FastAPI · REST API · SQLite · PostgreSQL |
| **Embedded** | Raspberry Pi · NFC · Camera · Thermal Printer · Touch Display |
| **Verification** | pytest · Playwright · GitHub Actions · Docker |
| **Product** | System Planning · UI/UX · Figma · Hardware Integration |

---

# How I Build

- **작게 시작합니다.** 문제와 사용 흐름을 정리하고 최소한의 동작부터 연결합니다.
- **경계를 확인합니다.** 화면·API·데이터·장치 간 계약과 실패 상태를 명시합니다.
- **근거를 남깁니다.** 테스트, 평가 자료, 실행 방법과 남은 한계를 함께 기록합니다.
- **검증을 구분합니다.** 샘플 시연, 소프트웨어 테스트, 실제 사용자·장치 검증을 같은 성과로 표현하지 않습니다.

# Currently

**Building & Improving**
- MirrorTing과 체험 키오스크의 대화·세션·리포트 연결
- 생강의 질문 기반 사고 훈련과 평가 방법
- 틈길의 역할별 서비스 흐름과 재현 가능한 MVP 검증

**Learning**
- Machine Learning · Deep Learning · NLP · Computer Vision
- LLM application architecture · Model evaluation · AI deployment
- AI × Product Design · Education · Physical Computing

---

# Highlights

### Awards

| Year | Award | Program · Competition |
| --- | --- | --- |
| 2026 | 우수상 | 학생참여형 리빙랩 활동 지원 프로그램 |
| 2026 | 우수상 | 태일씨앤티 웹사이트 리뉴얼 경진대회 |
| 2025 | 동상 | 한국실천공학회 교육장비개발대회 |
| 2025 | 동상 | AI로 만드는 우리 대학 이야기 공모전 |

### Activities

`2026 동양미래대학교 EXPO 본선` ·
`실전창업멘토링 및 IP 권리화 프로그램 본선(심화 멘토링 진행중)` ·
`도전! 메가시티 리그전 본선` ·
`D.StartupZone 입주 학생` ·
`AI Indie Game Hackathon`

---

<div align="center">

### Build AI that works beyond the demo.

**Learn · Build · Evaluate · Connect · Improve**

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-sdg331-181717?style=for-the-badge&logo=github)](https://github.com/sdg331)

</div>
