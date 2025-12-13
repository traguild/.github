# 모험가 길드 (Traveler Guild)

</br></br>

## 팀 구성원

<div align="center">

|                                           정호원                                            |                                           이준하                                            |                                           이진우                                            |
| :--------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------: |
| <img src="https://avatars.githubusercontent.com/u/76539118?v=4" width="150" alt="정호원" /> | <img src="https://avatars.githubusercontent.com/u/54894162?v=4" width="150" alt="이준하" /> | <img src="https://avatars.githubusercontent.com/u/50660496?v=4" width="150" alt="이진우" /> |
|                         [@ONE0x393](https://github.com/ONE0x393)                         |                          [@dlwnsgk](https://github.com/dlwnsgk)                          |                      [@dlwlsdn8864](https://github.com/dlwlsdn8864)                      |
|                                     Fullstack, Infra                                     |                                         Frontend(App)                                    |                                         Backend                                          |

</div></br></br>

## 📖 프로젝트 소개
**"지역 기반 의뢰 플랫폼, 모험가 길드"**

모험가 길드(Traguild)는 여행과 모험을 테마로 한 커뮤니티 중심의 크로스 플랫폼 애플리케이션입니다. 사용자들은 자신의 위치를 기반으로 주변의 의뢰(심부름, 잡일 등)를 수행하거나 직접 의뢰를 등록할 수 있으며, 이 과정에서 경험치와 칭호를 획득하는 게임 요소를 통해 재미를 느낄 수 있습니다. 또한, 여행 정보를 공유하고 실시간으로 소통할 수 있는 종합 커뮤니티 기능을 제공합니다.

- **프로젝트 기간:** 2024.09 ~ 2025.05 (약 8개월)

### ✨ 주요 기능
1. **의뢰 시스템 (Quest System)**
   - 주변의 간단한 의뢰를 지도에서 확인하고 수행할 수 있습니다.
   - 의뢰 완료 시 경험치 및 보상을 획득하여 '모험가 등급'을 올릴 수 있습니다.
2. **지도 및 위치 기반 서비스 (Map & Location)**
   - Google Maps 기반으로 내 위치 주변의 의뢰, 사용자, 핫플레이스를 탐색합니다.
3. **커뮤니티 및 채팅 (Community & Chat)**
   - 여행 정보 공유 게시판과 Socket.io를 활용한 실시간 채팅을 지원합니다.
4. **결제 시스템 (Payments)**
   - Toss Payments를 연동하여 안전하고 간편한 결제 환경을 제공합니다.
5. **통합 관리자 대시보드 (Admin Dashboard)**
   - 사용자 관리, 신고 처리, 시스템 모니터링을 위한 전용 웹 관리자 페이지를 운영합니다.

</br></br>

## 🛠 기술 스택 (Tech Stack)

### Frontend (App & Web)
<img src="https://img.shields.io/badge/React Native-61DAFB?style=flat-square&logo=react&logoColor=black"/> &nbsp;
<img src="https://img.shields.io/badge/Expo-1C2024?style=flat-square&logo=expo&logoColor=white"/> &nbsp;
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/> &nbsp;
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white"/> &nbsp;
<img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white"/>

### Backend
<img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=node.js&logoColor=white"/> &nbsp;
<img src="https://img.shields.io/badge/express-000000?style=flat-square&logo=express&logoColor=white"/> &nbsp;
<img src="https://img.shields.io/badge/socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white"/> &nbsp;
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/> &nbsp;
<img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white"/>

### Infrastructure
<img src="https://img.shields.io/badge/Amazon Web Services-252F3E?style=flat-square&logo=aws&logoColor=white"/> &nbsp;
<img src="https://img.shields.io/badge/NGINX-009639?style=flat-square&logo=nginx&logoColor=white"/> &nbsp;
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"/> &nbsp;
<img src="https://img.shields.io/badge/Github Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/>

### Tools & Collaboration
<img src="https://img.shields.io/badge/Google_Maps-4285F4?style=for-the-badge&logo=google-maps&logoColor=white"/> &nbsp;
<img src="https://img.shields.io/badge/Toss_Payments-0064FF?style=for-the-badge&logo=toss&logoColor=white"/> &nbsp;
<img src="https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white"/> &nbsp;
<img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white"/>

</br></br>

## 🏗 시스템 아키텍처 (System Architecture)
전체 시스템은 **MSA(Microservices Architecture)** 지향적으로 설계되었으며, 모바일 앱, 백엔드 서버, 관리자 웹, 결제 모듈이 유기적으로 연결되어 있습니다.

![Image](https://github.com/user-attachments/assets/ba221a09-093f-4fe5-97fd-303cc4bd15a0)

</br></br>

## 🔄 CI/CD 파이프라인
Github Actions를 활용하여 자동화된 빌드 및 배포 파이프라인을 구축했습니다.

### Back-end Pipeline
![Image](https://github.com/user-attachments/assets/c9734a3a-4663-4175-b25b-15c8a5010907)

### Frontend (App) Pipeline
![Image](https://github.com/user-attachments/assets/c4bd7764-f45e-4c2c-94d4-d71a944a5e92)

### Frontend (Web) Pipeline
![Image](https://github.com/user-attachments/assets/455c319d-ffa7-4fc9-8bc0-db15915188a4)