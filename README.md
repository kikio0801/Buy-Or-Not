# 🛒 Sa-Mara

[![Next.js](https://img.shields.io/badge/Next.js-16-black?logo=next.js&logoColor=white)](https://nextjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-4-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.135.1-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Pandas](https://img.shields.io/badge/Pandas-2.2-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white)](https://supabase.com/)
[![Playwright](https://img.shields.io/badge/Playwright-28211F?logo=playwright&logoColor=white)](https://playwright.dev/)
[![CodeRabbit](https://img.shields.io/badge/CodeRabbit-FF5A00?logoColor=white)](https://coderabbit.ai/)
[![License: All Rights Reserved](https://img.shields.io/badge/License-All_Rights_Reserved-red.svg)](#-라이선스-license)

## 🚀 브랜드 스토리 (Brand Story)

**"Sa-Mara"** 는 **"사? 말아?"** 라는 한국어 구어체 표현에서 영감을 받았습니다.  
온라인 중고거래 플랫폼을 보며 _"이 가격이 진짜 맞는 걸까? 이 사진이 진짜 상태랑 같을까?"_ 하고 끊임없이 고민하는 전 세계 소비자들을 위해 만들었습니다.

Sa-Mara는 꼼꼼한 AI의 눈으로 데이터를 검증하고, 이미지의 진위를 판별하며, 커뮤니티와 함께 구매를 결정하는 **글로벌 상거래 의사결정 플랫폼**입니다.

## 🌏 타겟 시장 (Target Market)

본 서비스는 **전 세계 중고거래(C2C eCommerce) 시장**을 타겟으로 합니다.  
eBay, Amazon, Carousell, Facebook Marketplace, Vinted, 당근마켓 등 글로벌 주요 플랫폼에서 발생하는  
**정보 비대칭성과 허위 이미지 문제를 해결**하고 사용자의 올바른 구매 의사결정을 지원하는 플랫폼입니다.

- **글로벌 커뮤니티**: 전 세계 사용자가 함께 투표하고 의견을 나누며, 집단 지성으로 구매 의사결정을 완성합니다.
- **AI 상품 분석**: 숨겨진 하자, 까다로운 거래 조건, 부풀려진 가격 등을 AI가 정밀하게 분석하여 위험 요소를 사전 방지합니다.
- **이미지 신뢰성 검증**: AI 생성 이미지 및 위변조 사진을 실시간으로 탐지하여 사기 거래를 사전에 차단합니다.
- **글로벌 인텔리전트 UX**: 브라우저 환경에 맞춘 자동 언어 감지와 12개 국어 실시간 전역 전환 기능을 제공하여 언어 장벽을 허뭅니다.

## ✨ 4대 핵심 기능

### 🗳️ 투표 커뮤니티 (Vote Community)

- **"산다 vs 안 산다"** 실시간 투표 시스템으로 전 세계 사용자의 집단 지성을 활용한 구매 결정 지원.
- Supabase Realtime 기반으로 다른 사용자의 투표가 즉시 반영되는 라이브 게이지 제공.
- 국가/언어별 필터링을 통해 본인에게 최적화된 매물 추천 및 소통 가능.

### 🤖 상품 분석 (Product Analysis)

- 중고거래 매물 URL 또는 사진 입력 시, AI가 시세·상태·판매자 신뢰도를 다각도로 자동 분석.
- **Honey Deal(꿀딜) / Fair Deal(보통딜) / Sour Deal(쓴딜)** 3단계 등급으로 직관적인 의사결정 가이드 제공. (글로벌 표준 명칭 적용)
- Crawl4AI 기반 실시간 데이터 수집 + Brave Search API 보조 탐색으로 최신 시세 반영.

### 📸 위변조 이미지 판별 (Fake Image Detector)

- 최신 딥러닝 모델로 Midjourney, FLUX 등 AI 생성 이미지를 고정밀도로 식별.
- 이미지 위변조 여부를 히트맵(Heatmap)으로 시각화하여 조작된 부분 직관적 확인 가능.
- 도용된 이미지나 합성 이미지의 패턴을 분석하여 사기 매물 선제적 탐지.

### 🌐 글로벌 하이퍼 캔버스 (Global UX)

- **자동 언어 감지**: 최초 접속 시 브라우저 설정을 분석하여 최적화된 언어로 즉시 셋팅.
- **12개 국어 전역 지원**: 한국어, 영어, 일본어, 중국어 등 전 세계 주요 12개 언어로 모든 UI와 분석 리포트를 완벽하게 번역.
- **실시간 로케일 동기화**: 페이지 이동이나 새로고침 시에도 중단 없는 사용자 경험 제공.

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
| **Database**   | Supabase (Realtime 포함)     |
| **Automation** | Playwright, Crawl4AI         |

### Data Analytics

| 분류           | 기술   |
| :------------- | :----- |
| **Processing** | Pandas |

### AI / ML

| 분류            | 기술                                       |
| :-------------- | :----------------------------------------- |
| **이미지 분석** | Transformer 앙상블 + 주파수 기반 탐지 모델 |
| **LLM 엔진**    | GitHub Copilot (GPT-4o)                    |
| **실시간 검색** | Brave Search API                           |

### Code Quality

| 분류            | 기술       |
| :-------------- | :--------- |
| **Code Review** | CodeRabbit |

## 🎬 데모 영상

Sa-Mara가 제공하는 분석 프로세스를 확인해 보세요.

- **데모 영상 (MP4)**: <br>[Sa-Mara.mp4](./documents/assets/Sa-Mara.mp4)
  <br>
  (view raw 클릭 해주세요!)

## 📄 라이선스 (License)

Copyright (c) 2026 **Yoon SangHwan** All Rights Reserved.

### ⚠️ 이용 안내

- 본 소프트웨어는 프로토타입입니다.
