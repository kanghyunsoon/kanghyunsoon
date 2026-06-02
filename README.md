# Kang Hyun Soon

> Backend developer with experience in Spring Boot services, external APIs, and real-time/game systems.

Spring Boot 기반 백엔드 개발과 외부 API 연동 서비스 구현에 관심이 있습니다.  
SSAFY 과정에서 Java, Spring Boot, MyBatis, MySQL을 중심으로 학습하고 있으며,  
공공데이터와 AI API를 활용한 위치 기반 서비스 프로젝트를 진행하고 있습니다.

이전에는 Unity와 Unreal Engine 기반 프로젝트를 통해  
게임 클라이언트 구조, 실시간 시스템, 네트워크 동기화, 서버 권위 구조를 경험했으며,  
현재는 이러한 경험을 백엔드 API 설계와 데이터 흐름 구현 역량으로 확장하고 있습니다.

---

## Tech Stack

### Backend
![Java](https://img.shields.io/badge/Java-17-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

### API / AI Integration
![TourAPI](https://img.shields.io/badge/TourAPI-External_API-blue?style=flat-square)
![Kakao Maps](https://img.shields.io/badge/Kakao_Maps-FFCD00?style=flat-square&logo=kakao&logoColor=black)
![Tmap](https://img.shields.io/badge/Tmap-API-blue?style=flat-square)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=google&logoColor=white)
![Google Cloud Vision](https://img.shields.io/badge/Google_Cloud_Vision-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

### Game / Real-time Systems
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![Unreal Engine](https://img.shields.io/badge/Unreal_Engine_4.27-0E1128?style=flat-square&logo=unrealengine&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

### Frontend
![Vue.js](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

---

## Main Projects

### Operation KOREA

TourAPI 공공데이터와 AI를 결합해 관광지를 위치 기반 야외 방탈출 미션으로 전환하는 관광 게이미피케이션 서비스입니다.

**Tech Stack**

- Java 17, Spring Boot, MyBatis, MySQL
- Spring Security, JWT
- TourAPI, Kakao Maps API, Tmap API
- Gemini API, Google Cloud Vision API

**My Role**

- 백엔드 REST API 구현
- RDBMS 스키마 설계
- JWT 기반 인증 흐름 구현
- TourAPI 기반 관광지 후보 데이터 연동
- Gemini / Vision API 기반 AI 인증 및 힌트 로직 연동

**What I Learned**

- 클라이언트 요청이 Controller, Service, Mapper, DB를 거쳐 응답으로 이어지는 백엔드 흐름
- MyBatis 기반 SQL 매핑과 RDBMS 테이블 설계의 중요성
- 여러 외부 API를 하나의 서비스 흐름에 연결할 때 필요한 예외 처리와 데이터 정제 과정

---

### The Way of Priest: Day and Night

Unity 기반 1인 개발 방치형 RPG 출시 프로젝트입니다.  
Google Play Store 출시 및 서비스 유지보수 경험이 있습니다.

**Tech Stack**

- Unity, C#
- Firebase Realtime DB
- Google Login, Leaderboard, AdMob
- Addressables, Object Pooling
- Offline Reward System

**Implemented Features**

- Firebase Realtime DB와 PlayerPrefs를 분리한 하이브리드 저장 구조
- Google Login, Leaderboard, AdMob 연동
- HTTP Header Date 기반 서버 시간 보정
- 오프라인 보상 및 시간 기반 디버프 시스템
- Object Pooling을 통한 반복 생성/삭제 비용 절감
- Addressables 기반 리소스 관리 구조

**What I Learned**

- 외부 SDK 연동 중 발생하는 버전 충돌과 빌드 문제 해결
- 서버/클라이언트 데이터 역할 분리
- 실시간 상태 관리와 메모리 최적화 구조 설계

---

### MultiPlayer TPS

Unreal Engine 4.27 기반 멀티플레이어 슈팅 프로토타입입니다.  
백엔드 지원 관점에서는 클라이언트-서버 구조, 서버 권위, 시간 동기화, 지연 보상 경험으로 정리하고 있습니다.

**Tech Stack**

- Unreal Engine 4.27
- C++
- Unreal Networking
- Replication / RPC

**Implemented Features**

- 서버 권위 기반 판정 구조
- RTT 기반 클라이언트-서버 시간 동기화
- 히트박스 히스토리 저장
- 과거 프레임 롤백 기반 지연 보상 기초 구현
- 캐릭터, 무기, HUD, 충돌 처리 구조 구현

**What I Learned**

- 클라이언트 데이터를 그대로 신뢰하지 않고 서버에서 검증하는 구조의 필요성
- 네트워크 지연이 판정과 상태 동기화에 미치는 영향
- 실시간 시스템에서 데이터 정합성을 유지하기 위한 상태 기록과 보간 방식

---

## Other Experience

- Unreal Engine 기반 Stealth Action RPG 프로토타입 제작
- 서울게임아카데미 SGA 프로그래밍 / Unreal Engine 교육 과정 수료
- SGA 우수학생 플레이X4 포트폴리오 영상출품
- SSAFY 15기 Java 풀스택 과정 진행 중


---

## GitHub Direction

현재 GitHub는 백엔드 지원을 중심으로 정리하고 있습니다.

- Main: Spring Boot, MyBatis, MySQL, JWT, External API
- Sub: Unity 출시 경험, Unreal Engine 실시간 시스템 경험
- Focus: 서비스 데이터 흐름, 인증, API 연동, 실시간 시스템 이해
