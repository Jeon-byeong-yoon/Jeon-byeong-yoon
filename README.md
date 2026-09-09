<div align="center">

# 전병윤 · Jeon Byeong Yoon

**AI 개발 도구를 활용해 더 효율적으로 문제를 해결하는 풀스택 개발자**

홍익대학교 세종캠퍼스 소프트웨어융합학과 · Data · AI · Database

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=github&logoColor=white)](https://jeon-byeong-yoon.github.io/portfolio/)
[![Tistory](https://img.shields.io/badge/Blog-EE5900?style=for-the-badge&logo=tistory&logoColor=white)](https://byoon2.tistory.com/)

</div>

---

## About

문제를 정확히 정의하고, 데이터를 꼼꼼히 정리하며, AI 모델과 서비스 구조가 목적에 맞게 작동하도록 만드는 과정에 집중합니다.

프로젝트를 진행하며 **좋은 결과는 모델 구조뿐 아니라 데이터 품질, 전처리 방식, 변수 구조, 학습 흐름을 체계적으로 관리하는 과정에서 나온다**는 점을 배웠습니다.

- 🎓 홍익대학교 세종캠퍼스 소프트웨어융합학과
- 🔭 관심 분야: 데이터 분석 · 인공지능 · 데이터베이스 · 시스템 설계
- 🌐 [포트폴리오](https://jeon-byeong-yoon.github.io/portfolio/) · [기술 블로그](https://byoon2.tistory.com/)

---

## Tech Stack

**Language**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

**Database**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![ERD](https://img.shields.io/badge/ERD-336791?style=flat-square)

**AI · Data**

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![LSTM](https://img.shields.io/badge/LSTM-5C3EE8?style=flat-square)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-412991?style=flat-square&logo=openai&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

---

## Projects

### 🏆 LG Aimers 9기 — 야구 투구 제구 성공 확률 예측
> LG AI연구원 해커톤 Phase 2 · 3인 팀 (모델링 · 실험 설계 · 제출 파이프라인)

KBO 리그 실제 투구 데이터와 Trackman 측정 로그로 투구의 제구 성공 확률을 예측하는 이진 분류 과제.
공식 Random Forest 베이스라인(Public **900.7385**)에서 출발해 약 **210차례 실험**을 거쳐, 6개 모델 가중 블렌드 위에 세그먼트 보정층을 얹은 구조로 Public **1083.2462**(+182.5)에 도달했습니다.

- 6성분 가중 블렌드(HistGradientBoosting · CatBoost · 엔티티 임베딩 신경망 등) + 볼카운트·좌우스플릿 축 잔차 보정층 설계
- 2022~2024 시간순 폴드 검증을 리더보드와 짝지어 효과의 부호·유의성을 판정 — 16번 중 14번 방향 적중
- 평가 서버와 동일한 런타임 환경 게이트를 두어 제출 무효화 사전 차단

`Python` `CatBoost` `HistGradientBoosting` `Entity Embedding` `Ensemble` `Calibration` `Time-Series CV`

### 📡 착용형 UWB 실내 낙상 관제 시스템
> 해커톤 2차 본선 · 5인 팀 (서버 측위 파이프라인 · 경보 상태 UX 담당)

노인요양시설 대상 실내 위치·낙상 관제 시스템. 카메라 대신 착용형 UWB 태그로 위치를, 내장 가속도계로 낙상을 감지해 **CCTV가 법으로 금지된 화장실·목욕실까지 관제 범위**에 포함했습니다.

- 실기기 없이 개발하도록 50Hz 원시 신호 생성기 + NDJSON 리플레이 하네스 선구축
- 방향 센서 없이 두 앵커 거리만으로 좌표를 구하는 반평면 삼각측량 구현 (복원 오차 1mm 검증)
- 경보 UX를 DOM과 분리된 상태 저장소로 재구성 — 이벤트 ID가 바뀌어도 태그 단위 lifecycle 유지

`TypeScript` `Node.js` `UWB` `Trilateration` `SSE` `Signal Smoothing`

### 🧭 CodeVi — 코드 시각화 · 품질 분석 플랫폼
> 캡스톤 디자인 · 5인 팀 (백엔드 메트릭 API · 분석 파이프라인 연동 · 인증 담당) · 비공개 저장소

소스 코드의 AST를 추출해 Directory → File → Class → Function 계층을 인터랙티브 노드-엣지 그래프로 시각화하고, 복잡도·결합도 지표로 리팩토링 지점을 드러내는 플랫폼입니다.

- 코드 품질 메트릭 API를 MVP까지 구현 — Cyclomatic Complexity, Halstead, CBO/RFC/LCOM 등 산출 및 저장
- 원격 파서 API 연동과 ZIP 업로드 분석 프록시 엔드포인트를 붙여 GitHub·로컬 코드 양쪽 온보딩 경로 확보
- 전역 응답 포맷(`ApiResponse`) 인터셉터로 API 계약을 통일하고 Swagger Bearer 인증 적용
- Kakao OAuth 소셜 로그인 구현, CodeVi 분석용 Jenkinsfile 작성으로 빌드 후 자동 스냅샷 연결

`NestJS` `TypeScript` `TypeORM` `MySQL` `React` `Tree-sitter` `SonarQube` `Jenkins` `Docker`

### 그 외 프로젝트

| 프로젝트 | 설명 | 기술 |
| --- | --- | --- |
| 딥페이크 탐지 이진 분류 | 프레임 분리·얼굴 크롭·노이즈 제거로 학습 데이터 품질을 개선한 실제/생성 영상 판별 모델 | `Python` `Binary Classification` |
| 119 신고 건수 예측 | 소방 데이터와 기상청 날씨 데이터를 결합, 12개 지점별 전처리 후 시계열 예측 | `TensorFlow` `Keras` `LSTM` |
| 헬스케어 DB 설계 | 사용자·신체정보·활동·수면·영양·체중 엔터티를 분리하고 PK/FK 관계를 정의한 관계형 DB | `MySQL` `ERD` `SQL` |

---

## Repositories

| 레포 | 설명 |
| --- | --- |
| [kbo-ai-brief](https://github.com/Jeon-byeong-yoon/kbo-ai-brief) | KBO 경기 정보 + AI 프리뷰/리뷰 웹 앱 (준실시간 경기 정보 서비스) |
| [code-smell-detection-mcp](https://github.com/Jeon-byeong-yoon/code-smell-detection-mcp) | 정적 분석 / 코드 스멜 탐지용 MCP 서버 (Node·TypeScript stdio transport) |
| [portfolio](https://github.com/Jeon-byeong-yoon/portfolio) | 개인 포트폴리오 웹사이트 (GitHub Pages) |
| [community_be](https://github.com/Jeon-byeong-yoon/community_be) | 커뮤니티 서비스 백엔드 (Java) |
| [metaverse-course-projects](https://github.com/Jeon-byeong-yoon/metaverse-course-projects) | 메타버스 교과 프로젝트 모음 (Java) |

---

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=Jeon-byeong-yoon&show_icons=true&hide_border=true&include_all_commits=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Jeon-byeong-yoon&layout=compact&hide_border=true&langs_count=8)

</div>
