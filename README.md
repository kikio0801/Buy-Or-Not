# 🛒 SureAnnot (SureAnnot)

[![Next.js](https://img.shields.io/badge/Next.js-16-black?logo=next.js&logoColor=white)](https://nextjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-4-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.135.1-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Pandas](https://img.shields.io/badge/Pandas-2.2-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white)](https://supabase.com/)
[![Playwright](https://img.shields.io/badge/Playwright-28211F?logo=playwright&logoColor=white)](https://playwright.dev/)
[![CodeRabbit](https://img.shields.io/badge/CodeRabbit-FF5A00?logoColor=white)](https://coderabbit.ai/)
[![License: All Rights Reserved](https://img.shields.io/badge/License-All_Rights_Reserved-red.svg)](#-라이선스-license)

## 🚀 브랜드 스토리 (Brand Story)

**"SureAnnot"** 은 싱가포르 국민이라면 누구나 매일 쓰는 친숙한 싱글리시(Singlish) 표현 **"Sure, anot?" (진짜야? 정말 확실해?)** 에서 영감을 받았습니다.
온라인 중고거래나 부동산 매물을 보며 "이 가격이 진짜 맞는 걸까? 이 매물 상태가 정말 사진과 같을까?" 라며 끊임없이 **"Sure, anot?"** 을 외치는 싱가포르 사람들을 위해 만들었습니다..
SureAnnot은 꼼꼼한 AI의 눈으로 데이터를 꼼꼼하게 검증하고 매물의 가치를 평가하여, 의심 가득한 "Sure, anot?" 이라는 질문에 **"Yes, Sure!"** 라는 확실한 답을 찾아주는 플랫폼입니다.

## 🌏 타겟 시장 (Target Market)

본 서비스는 **싱가포르 중고거래(eCommerce) 및 부동산 시장**을 1차 타겟으로 합니다.
Carousell, PropertyGuru 등 싱가포르 주요 플랫폼에서 발생하는 정보 비대칭성을 해결하고 사용자의 올바른 구매 의사결정을 지원하는 **"상거래 의사결정 플랫폼"** 입니다.
망설여지는 순간, 친근하고 꼼꼼한 AI의 시선으로 매물의 가치를 진단하고 최적의 선택을 도와드립니다.

- **정보 불균형 해소**: 숨겨진 하자, 까다로운 거래 조건, 부풀려진 가격 등을 AI가 분석하여 위험 요소를 사전 방지합니다.
- **다각도 가치 평가**: 시세 단순 나열을 넘어 이상치 패턴(초저가 사기/비정상 고가)을 필터링하고 통계적 통찰을 제공합니다.

## ✨ 핵심 기능

- **🤖 AI 심층 분석 엔진**: 최신 데이터 실시간 수집 및 다각도 매물 가치 평가.
- **📸 AI 생성 이미지 진위 여부 탐지 파이프라인 (Fake Image Detector)**:
  - 실생활 이미지와 AI 생성물 비교 실험을 통해 도출된 **최적의 주파수 임계치**를 바탕으로과 최신 딥러닝 **Transformer 앙상블** 모델을 결합하여, Midjourney, FLUX 등 초고화질 AI 생성 이미지를 높은 정밀도로 식별합니다.
  - 복합 이미지(Collage) 분할 분석 기술을 통해 여러 장이 합쳐진 이미지 내의 AI 생성 요소까지 놓치지 않고 탐지합니다.
- **💧 직관적인 등급 시스템**:
  - **꿀 딜 (Sweet Deal)**: 매력적인 가격과 조건의 강력 추천 매물.
  - **보통 딜 (Plain Deal)**: 시장 시세에 부응하는 일반적인 매물.
  - **씁쓸한 딜 (Bitter Deal)**: 위험 요소가 감지된 주의 필요 매물.
- **🕵️‍♂️ 판매자 평판 분석**: 판매자의 활동 이력을 추적하여 전문 업자 여부 및 거래 신뢰도를 판정.
- **📈 대물림 지수**: 과거 동일 매물 가격 대조를 통해 재판매 여부 및 적정 프리미엄 확인.
- **🔍 3줄 핵심 요약**: 장황한 설명문에서 핵심 제약 조건만 AI가 빠르게 요약 제공.

## 🛠 기술 스택

### Frontend

| 분류             | 기술                                 |
| :--------------- | :----------------------------------- |
| **Core Stack**   | Next.js 16 (App Router) + TypeScript |
| **Optimization** | **React Compiler** 활성화            |
| **Styling**      | Tailwind CSS 4 + Shadcn UI           |
| **State Mgt**    | Zustand                              |

### Backend

| 분류           | 기술                         |
| :------------- | :--------------------------- |
| **Core Stack** | FastAPI, Uvicorn (서버 엔진) |
| **Database**   | Supabase                     |
| **Automation** | Playwright                   |

### Data Analytics

| 분류           | 기술   |
| :------------- | :----- |
| **Processing** | Pandas |

### Code Quality

| 분류            | 기술       |
| :-------------- | :--------- |
| **Code Review** | CodeRabbit |

## 🎬 데모 영상

SureAnnot가 제공하는 분석 프로세스를 확인해 보세요.

- **데모 영상 (MP4)**: <br>[documents/assets/Video_Project.mp4](./documents/assets/documents/assets/Video_Project.mp4)
  <br>
  (view raw 클릭 해주세요!)

## 📄 라이선스 (License)

Copyright (c) 2026 **Yoon SangHwan** All Rights Reserved.

### ⚠️ 이용 안내

- 본 소프트웨어는 프로토타입입니다.
