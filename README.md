<h1 align="center">Seo Jaeyoung!</h1>

<p align="center">
백엔드 중심 풀스택 개발자를 목표로 공부하고 있습니다.<br>
🌱 Spring Boot 기반 REST API 설계와 백엔드 개발 경험을 쌓고 있습니다.<br>
🔍 문제의 원인을 분석하고 해결하는 과정과 로직 설계를 좋아합니다.<br>
🤖 모바일 로보틱스 대회 경험을 통해 문제 해결 능력을 키웠습니다.
</p>  
<p align="center">

[![Email](https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kingom5437@naver.com)
[![Velog](https://img.shields.io/badge/BLOG-20C997?style=for-the-badge&logo=velog&logoColor=white)](https://velog.io/@seojaeyeong-051/series)

</p>

---

## 🛠 Tech Stack

### Backend
<p>
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge)
![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge)
![Spring Security](https://img.shields.io/badge/SpringSecurity-6DB33F?style=for-the-badge)
![JPA](https://img.shields.io/badge/JPA-59666C?style=for-the-badge)
</p>

### Frontend
<p>
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge)  
</p>

### Database
<p>
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge)  
</p>

### DevOps
<p>
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge)
![GitHub Actions](https://img.shields.io/badge/GitHubActions-2088FF?style=for-the-badge)  
</p>

### Robotics
- AVR 마이크로컨트롤러 기반 임베디드 시스템
- IR / ID 센서를 활용한 라인트레이싱 및 경로 제어
- 카메라 기반 퍽(Puck) 객체 인식
- AGV / 모바일 로보틱스 시스템

---

## 🚀 About Me

👨‍💻 Spring Boot 기반 백엔드 개발을 중심으로 풀스택 개발을 공부하며 프로젝트를 진행하고 있습니다.

🧩 REST API 설계, 인증/인가(JWT · OAuth2), DB 모델링을 통해 서비스 기능을 구현하는 과정에 흥미를 느낍니다.

🐞 에러를 단순히 해결하는 것에서 끝내지 않고  
재현 → 로그 분석 → 원인 파악 → 수정 → 기록(회고)까지 이어지는 문제 해결 과정을 중요하게 생각합니다.

🤝 팀 프로젝트에서 branch / PR / merge 기반 협업을 경험했고  
merge conflict 해결과 코드 통합 과정을 통해 협업 능력을 키웠습니다.

🤖 과거 전국 기능경기대회 모바일 로보틱스 은메달 수상 경험이 있습니다.  
대회 경험을 통해 로직 설계와 문제 해결 과정에 흥미를 가지게 되었고  
현재는 이를 백엔드 개발 역량으로 확장하고 있습니다.

---

## 📂 Projects

<details>
<summary>🤖 Mobile Robotics Competition</summary>

AVR 기반 모바일 로봇 프로젝트  
3 Omni Wheel Robot + Sensor Navigation

**기간**
2018.9 ~ 2020.9

**인원**
2인 팀 프로젝트

**역할**

- 하드웨어 구성 및 센서 연동
- 헤더 파일 작성 및 코드 구조 설계
- 동작 미션 로직 구현
- 로봇 동작 로직 수정
- 실제 경기 환경 테스트 및 디버깅

🏅 **2019 지방 기능경기대회 모바일 로보틱스 동메달**
🏅 **2020 지방 기능경기대회 모바일 로보틱스 은메달**
🏅 **2020 전국 기능경기대회 모바일 로보틱스 은메달**

🔗  
https://github.com/jaeyoung051/MobileRobotics-Portfolio
</details>
---

<details>
<summary>🏠 ShareStay (룸 쉐어링 플랫폼)</summary>

지도 기반으로 방을 탐색하고 예약할 수 있는 **공유 주거 플랫폼**

**기간**  
2025-10-29 ~ 2025-12-10

**인원**
5인 팀 프로젝트

**역할**  
Backend 중심 Full-stack (API 설계/구현 + 인증 시스템)
---
### 핵심 기능

- 카카오맵 API 기반 지도 방 탐색 기능
- 방 목록 조회 / 필터 / 정렬 / 상세 조회 및 공유 링크 생성
- 찜(Bookmark) 및 좋아요 기능
- JWT 기반 인증 및 Google OAuth2 소셜 로그인 연동
- Role 기반 권한 분리 (USER / ADMIN) 및 관리자 사용자 밴 기능
---
### 기술 스택

**Frontend**

React / TypeScript / MUI

**Backend**

Spring Boot / Spring Security / JPA / JWT / OAuth2

**Database**

MariaDB
---

### Troubleshooting

프로젝트 진행 중 발생한 주요 이슈를 분석하고 해결했습니다.

📎 Velog 정리  
https://velog.io/@seojaeyeong-051/series/TeamProject-sharestay

- 인증 구조 충돌 (Cookie vs SessionStorage) 문제 해결  
- OAuth2 Redirect 경로 문제 해결 (로그인 후 원하는 페이지 이동 실패)  
- React + MUI 타입 오류 해결  
- Git merge 충돌 및 fast-forward 오류 해결  
- Nginx + HTTP 배포 구성 오류 해결  
- 공유 링크 생성 로직 변경 후 발생한 버그 수정  

---

🔗 Repository  
https://github.com/RoomShareProject/sharestay

</details>

---
<details>
<summary>📋 Backend MVP</summary>

Spring Boot 기반 REST API 구조를 연습하기 위한 개인 프로젝트

**구현 기능**

- 게시판 CRUD API
- 사용자 로그인 인증
- REST API 구조 설계

**확장 계획**

향후 해당 프로젝트를 기반으로  
요트 예약 플랫폼의 **예약 관리 / 스케줄 관리 / 상태 관리 시스템**으로 확장할 예정입니다.

🔗 Repository  
https://github.com/jaeyoung051/backend-mvp

</details>
---

## 📊 GitHub Stats
<p align="center">
  
![Jaeyoung's GitHub stats](https://github-readme-stats.vercel.app/api?username=jaeyoung051&show_icons=true&theme=tokyonight)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=jaeyoung051&layout=compact&theme=tokyonight)

</p>
