# 👋 Kim Seungkyu

## Skills

### Languages
<img src="https://img.shields.io/badge/kotlin-7F52FF?style=for-the-badge&logo=android&logoColor=white"/> <img src="https://img.shields.io/badge/java-4B4B77?style=for-the-badge&logo=java&logoColor=white"/> <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"/> 
<img src="https://img.shields.io/badge/c++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white">

### Tech

<img src="https://img.shields.io/badge/android-3DDC84?style=for-the-badge&logo=android&logoColor=white"/> <img src="https://img.shields.io/badge/jetpackcompose-4285F4?style=for-the-badge&logo=compose&logoColor=white"> <img src="https://img.shields.io/badge/firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white">


## Experience

🏛️ 한양대학교 ERICA 컴퓨터학부 졸업

📱 네이버 부스트캠프 9기 안드로이드 수료

## Article

📀 오디오 시각화 라이브러리 개발과정 : https://velog.io/@miller198/series/AudioVisualize


## Project

### MusicRoad : 지도 기반 음악 공유 및 스트리밍 서비스(24.11 - 24.12 개발, 25.02 - 25.06 개선)
- 기술스택: Kotlin, ExoPlayer, Jetpack Compose, Retrofit, Coil, OkHttp, Firebase, NaverMapSDK 등
- 담당역할
1) ExoPlayer를 활용한 음악 **스트리밍 플레이어** 구현
2) Raw 오디오 데이터를 가공하여 실시간 주파수 기반 **오디오 비주얼라이저** 구현
3) 빌드 속도 개선 및 의존성 관리를 위한 **Feature 단위 모듈 분리** 및 Convention Plugin 도입
4) 오디오 시각화 모듈의 독립 라이브러리화 이후 **오픈소스로 배포**
- Github: https://github.com/boostcampwm-2024/and06-musicroad
- 스토어: https://play.google.com/store/apps/details?id=com.squirtles.musicroad

### ComposeCircleAudioVisualizer : 오디오 시각화 라이브러리
- https://github.com/miller198/ComposeCircleAudioVisualizer
- 기술스택:Kotlin, Jetpack Compose, Android Visualizer API, Digital Signal Processing (DSP), Gradle, JitPack
- 담당역할: 개발 전체
- 주요 작업
  1) DSP 알고리즘 설계
  2) 렌더링 엔진 최적화
  3) 라이브러리 배포 및 문서화


###  DoRunDoRun: 친구와 함께하는 러닝 인증 서비스 (25.08 - 25.11)
- 기술스택: Kotlin, Jetpack Compose, Hilt, Coroutines, Room, Paging3, Orbit MVI, Naver Map SDK, FCM, Coil 등
- 담당역할
1) 실시간&백그라운드 러닝 트래킹 및 드로잉 등 **러닝 기능 전체** 담당
2) 클린 아키텍처 & MVI 기반 베이스 아키텍처 설정
- 주요 작업
  1) Foreground Service를 활용하여 백그라운드에서도 끊김 없는 러닝 데이터(시간, 거리, 페이스, 케이던스) 측정, 실시간 러닝 경로 드로잉 등 모든 러닝 기능
  2) 러닝 중 앱 종료에도 러닝 데이터 무결성 유지
  3) Clean Architecture & MVI 패턴으로 프로젝트 기초 설계를 주도해 유지보수 용이한 코드 구조 수립
- Github: https://github.com/depromeet/17th-team6-android
- 스토어: https://play.google.com/store/apps/details?id=com.dpm.sixpack

### sou.zip : 위치 기반 기념품 정보 및 공유 서비스 (25.11 - 26.01, 고도화 및 운영 중)
- 역할: 안드로이드 개발 전체 담당
- 기술스택: Kotlin, Jetpack Compose, Hilt, Coroutines/Flow, Mapbox SDK, OAuth(Kakao/Google), Paging3, Coil 등
- Key Tasks
  1) 서버 토큰 자동 갱신 메커니즘과 동시성 제어
  2) 최신 Navigation3 학습 및 적용
  2) 다수의 이미지의 효율적인 업로드를 위한 이미지 리사이징 및 최적화
  3) PM/디자이너/백엔드개발자와 직접 소통하며 효율적인 API 구조 제안 및 UI 인터랙션 고도화
- 성과
  1) 앱 3기 대상 수상
  2) 이미지 최적화로 업로드와 UI 표시되는 사진의 크기 및 load 시간 80% 단축
- Github: https://github.com/souzip/souzip-android
- 스토어: https://play.google.com/store/apps/details?id=com.swyp.souzip
