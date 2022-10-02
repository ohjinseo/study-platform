# Jadu-Study-Platform

### ⏲️ 개발기간
2022년 07월 18일 ~ 2022년 09월 15일

---
### 👨‍👩‍👧‍👧 팀원구성
|  이름  |  포지션  |
| :----: | :-----: |
| [오진서](https://github.com/ohjinseo)|BE / Spring [팀장]|
| [정연재](https://github.com/jyjae)|BE / Spring|
| [민진기](https://github.com/Dmin3)|BE / Spring|
| [강전호](https://github.com/zzho-o)|FE / React|

---
### ⭐️ 프로젝트 주요 기능
- 계정은 카카오, GitHub 계정 또는 일반 계정으로 나누어진다.
- 회원은 스터디에 참여하거나 스터디방을 개설할 수 있다.
- 스터디 방은 일반 스터디 방과 프로젝트 방으로 분류되며, 프로젝트일 시 각 기술 스택 별로 모집할
수 있다.
- 사용자끼리 1:1 채팅을 할 수 있으며, 스터디 방 참여 시 스터디 그룹 채팅과 그룹 화상회의를 통해
스터디를 진행할 수 있게 된다.
- 스터디 그룹 화상회의 진행 중 동시에 그룹 채팅이 가능하며, 발언자 감지 기능, 음소거, 화면 닫기
등의 기능이 포함되어 있다.
- 1:1 채팅 같은 경우 참여하고 있지 않을 시 안읽은 메시지 개수가 업데이트 되며, 알람이 발송된다.
- 스터디 방에서 방장은 목표 설정이나 스터디 캘린더를 통해 일정을 정할 수 있게 된다.
- 스터디 방의 캘린더 일정은 자동으로 스터디원 개인의 캘린더에 동기화가 이루어져 개인 캘린더에서
참여한 스터디의 모든 일정을 확인할 수 있게 된다.
---
### 🖥 Backend 개발 환경
| 기술스택/툴 | 버전 | 설명 |
| ------ | ----------- | ----------- |
| Intellij   | 상관 없음  | Ide      |
| Java   | 11  | 자바 버전      |
| Gradle   | 7.5    | gradle       |
| Spring Boot   | 2.7.2                 | 프레임워크       |
| Spring JPA   | 2.7.2                 | 프레임워크       |
| Mysql   | 8.0.28 | 데이터베이스       |
| Mysql Workbench   | 8.0            | mysql client        |
| Jar   |          | 패키징       |
| Redis   | 2.7.2            | 데이터베이스       |
| STOMP   | 2.3.3-1            | WebSocket      |
| Springdoc-Openapi-Ui  | 1.6.11            | API DOCS       |
---
### 🖥 Devops 개발 환경
| 기술스택/툴 | 버전 | 설명 |
| ------ | ----------- | ----------- |
| EC2   | ...  | AWS EC2      |
| S3   | ...  | AWS S3      |
| RDS   | ...    | AWS RDS       |
| CodeDeploy   | ...    | AWS CodeDeploy       |
| Nginx   |  ...                |   웹서버     |
| GithubAction   | ...            | CI/CD      |
| Docker   | ...            | ...      |
| Docker-compose   | ...            | ...      |
| Openvidu-Server  |  2.18.0           | WebRTC       |
---  
### 💡 서비스 아키텍처
![서비스 아키텍처](https://user-images.githubusercontent.com/80299170/190058923-c197377a-a728-4971-8f56-930750177443.png)

---
### ⭐️ ERD
![ERD2](https://user-images.githubusercontent.com/80299170/190061526-069dbf27-8f4a-4e64-ba77-b6be820cf98b.png)

