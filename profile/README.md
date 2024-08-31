![image](https://github.com/user-attachments/assets/535b0945-5d9b-4847-a742-86794c89fdee)
# 돈기부여 👋

## 예치금을 걸고 금융 목표에 도전하는 SOL인앱 챌린지 서비스

- 길치들을 위한 목적지 경로 제공으로 안전하게 도착해보세요 !
- 친구들끼리 그룹을 만들고 모임을 효과적으로 관리해보세요 !

## 기능 소개

### 👍 커피,술,배달비 줄이기 챌린지!

- 목적지를 카테고리 별, 키워드 별 검색으로 손쉬운 설정이 가능합니다.
- 목적지와 함께 약속을 생성해 미리 목적지 정보를 공유할 수 있답니다!

### 🎯 행운의 777적금 ~!

- 약속장소와 가까운 핵심 스팟 정보를 통해 쉽게 장소를 찾아보세요.
- 그룹원의 중간지점 또한 알 수 있어 쉽게 만날 수 있습니다!

### 🛣️ 매일매일 금융 퀴즈 챌린지!

- 지도를 통해 목적지로 가는 길을 빠르게 알 수 있어요.
- 실시간으로 제공되는 경로를 따라가다 보면 목적지가 보인답니다!

### 🗺️ 참여하는 챌린지의 채팅방에 참여하여 소통

- 약속에 포함된 친구들의 현재 위치를 한 번에 확인할 수 있어요.
- 길을 잃은 친구를 바로 파악할 수 있답니다!

### 📱 FCM을 응용한 실시간 알림 / Slack Message

- 길을 찾기 어려운 경우 그룹 통화가 가능합니다.
- 다 같이 경로에 대한 정보를 공유해 빠르게 모여보세요!


## 시스템 아키텍처
![image](https://github.com/user-attachments/assets/43841537-53ea-4e56-a7c9-87d967188447)

## DB ERD
![image](https://github.com/user-attachments/assets/e47e4d62-4975-4be6-b0af-432b978ef976)

## 사용 기술
|Frontend|Backend|Infra/DevOps|
|:---:|:---:|:---:|
|<img src="https://img.shields.io/badge/react-F05138?style=for-the-badge&logo=React&logoColor=white"><br><img src="https://img.shields.io/badge/typescript-F1007E?style=for-the-badge&logo=typescript"><br><img src="https://img.shields.io/badge/nextjs-F1007E?style=for-the-badge"><br><img src="https://img.shields.io/badge/reactquery-2396F3?style=for-the-badge&logo=reactquery&logoColor=white">|<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=OpenJDK&logoColor=white"><br><img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"><br><img src="https://img.shields.io/badge/hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white"> <br> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"><br><img src="https://img.shields.io/badge/stomp-010101?style=for-the-badge">|<img src="https://img.shields.io/badge/amazonrds-569A31?style=for-the-badge&logo=amazonrds&logoColor=white"><br><img src="https://img.shields.io/badge/amazonec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"><br><img src="https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white"><br><img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"><br><img src="https://img.shields.io/badge/slack-2496ED?style=for-the-badge&logo=slack&logoColor=white"><br><img src="https://img.shields.io/badge/firebase-2496ED?style=for-the-badge&logo=firebase&logoColor=white">|

## 구현적 특징
### Frontend
1. 그룹원들간의 실시간 위치 공유를 위해 WebSocket과 RabbitMQ pub/sub를 사용했다.
2. Naver와 T-MAP API를 사용하여 목적지에 대한 보행자와 자동차 경로를 제공한다.

### Backend
1. 그룹원들간의 실시간 위치 공유를 위해 WebSocket과 RabbitMQ pub/sub를 사용했다.
2. Naver와 T-MAP API를 사용하여 목적지에 대한 보행자와 자동차 경로를 제공한다.


## 멤버 소개
|박수진|이윤하|곽성재|진주원|정연서|
|:----:|:----:|:----:|:----:|:----:|
|Frontend|Frontend|Frontend|Backend|Backend|
|[@s0ojin](https://github.com/s0ojin)|[@yoonha97](https://github.com/yoonha97)|[@kwakseongjae](https://github.com/kwakseongjae)|[@jinjoo-lab](https://github.com/jinjoo-lab)|[@yeondori](https://github.com/yeondori)|
 | <img src = "https://avatars.githubusercontent.com/u/100757599?v=4" width ="120" height = "150"> | <img src = "https://avatars.githubusercontent.com/u/155246172?v=4" width ="120" height = "150">| <img src = "https://avatars.githubusercontent.com/u/87296259?v=4" width ="120" height = "150">| <img src = "https://avatars.githubusercontent.com/u/84346055?v=4" width ="120" height = "150">| <img src = "https://github.com/user-attachments/assets/ef45be79-0342-4d18-bd78-bf86388824d4" width ="120" height = "150">|
