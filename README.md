# 5차 프로젝트 - **대장부(Captain Book) 개인프로젝트 (captain book project)**

## 💡 개인 :대장부(Captain Book) 프로젝트

<img width="350" height="350" alt="DaeJangBu-radius-logo" src="https://github.com/user-attachments/assets/cb7f16af-1c36-4f55-b2e9-54b7f24ff938" />

<br><br><br>

- 메인 페이지: https://.. (아직은 미배포 상태입니다.)

<br><br>

---
### 리포지터리 링크

* **소개 링크 :** https://github.com/yoda-yoda/project5-captain-book-overview
* **backend (spring) :** https://github.com/yoda-yoda/project5-captain-book-backend
* **frontend (react) :** https://github.com/yoda-yoda/project5-captain-book-frontend

<br><br>

---

## 개요

# 5차 프로젝트 - **대장부(Captain Book) 개인프로젝트 (captain book project)**

## 💡 개인 :대장부(Captain Book) 프로젝트

<img width="350" height="350" alt="DaeJangBu-radius-logo" src="https://github.com/user-attachments/assets/cb7f16af-1c36-4f55-b2e9-54b7f24ff938" />

<br>

### 주제

- 웹 가계부 어플리케이션을 구현하였습니다.

<br>

### 대장부(Captain Book)의 의미  
- **대장부(Captain Book) =>** '대장부'란 단어는 '무언가를 기록하는 큰 장부', '크고 씩씩한 사람'이라는 뜻을 동시에 담고있어 차용하였습니다. <br> '대장부'를 영어로 'Captain Book' 으로 표현했습니다.



<br><br>

---


## 🌟 주요 기능

<br>

### 1. 달력 기능
   - 날짜별로 세부 아이템을 저장할 수 있는 달력 기능 구현
   - 날짜, 제목 설정 가능
   - 달력 저장 및 조회, 수정, 삭제 기능

### 2. 아이템 기능
   - 해당 달력안에서 세부 항목을 기록하는 아이템 기능 구현
   - 아이템 이름, 금액, 종류 설정 가능 
   - 아이템 저장 및 조회, 수정, 삭제 기능

### 3. 폼(Form) 로그인
   - JWT 액세스 토큰 인증 기반, 리프레시 토큰으로 로테이션 전략 구현
   - '직접 가입하기', '직접 로그인' 으로 대장부 웹사이트 전용 계정으로 직접 폼가입 및 폼로그인 가능
   - 폼 회원 userId 중복 불가 처리
   - 로그아웃 기능 (JWT 액세스 토큰, 리프레시 토큰 삭제 기능 구현)

### 4. 오아스(OAuth) 로그인
   - JWT 액세스 토큰 인증 기반, 리프레시 토큰으로 로테이션 전략 구현
   - 소셜 로그인(Google) 기반 OAUTH 2.0 로그인 가능 (Naver, Kakaao는 추후 구현 예정입니다.)
   - 최초 로그인 시 자동 DB 회원가입 처리  
   - 로그아웃 기능 (JWT 액세스 토큰, 리프레시 토큰 삭제 기능 구현)



<br><br>

---

## 🚀**개발 환경**

<br>



- ### 아키텍처

<img width="1792" height="1063" alt="최종아키텍처-captain-book" src="https://github.com/user-attachments/assets/66b3894a-2a79-4755-95f4-1e1a1cd18a32" />

<br><br><br>


- ### **ERD(Spring)**

<img width="1480" height="789" alt="DBerd" src="https://github.com/user-attachments/assets/839bb021-5658-4cfe-887f-910f6b846e42" />


<br><br>



- ### **플로우 차트**

**(전체)**

<img width="525" height="618" alt="flow-전체captain-book" src="https://github.com/user-attachments/assets/81803360-7e2e-4005-8852-c718555beaed" />

<br><br>

**(달력 기능)**
<img width="1350" height="550" alt="flow-달력기능-captain-book" src="https://github.com/user-attachments/assets/78a7d579-04b0-4ac1-93ba-fd6d7edd2644" />

<br><br>

**(아이템 기능)**

<img width="1348" height="552" alt="flow-아이템기능-captain-book" src="https://github.com/user-attachments/assets/ceae2b6d-3d46-4585-9d9f-330563c14e7b" />

<br><br>

**(로그인, 로그아웃 기능)**

<img width="1353" height="447" alt="flow-로그인-로그아웃기능-captain-book" src="https://github.com/user-attachments/assets/2d924c11-6327-4f21-9a45-97c01f902c0d" />

<br><br>

- ### **활용 기술**


<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="https://img.shields.io/badge/JAVA-a?style=for-the-badge&logo=JAVA&logoSize=auto&color=%23946951">
  <img src="https://img.shields.io/badge/SPRING-a?style=for-the-badge&logo=spring&logoColor=white&logoSize=auto">
  <img src="https://img.shields.io/badge/SECURITY-a?style=for-the-badge&logo=spring%20security&logoColor=white&logoSize=auto&color=%23419e5d">
  <img src="https://img.shields.io/badge/JWT-a?style=for-the-badge&logo=jsonwebtokens&logoColor=white&logoSize=auto&color=%23be48c2">
  <img src="https://img.shields.io/badge/DOCKER-a?style=for-the-badge&logo=docker&logoColor=white&logoSize=auto&color=%232496ED">
  <img src="https://img.shields.io/badge/REDIS-a?style=for-the-badge&logo=redis&logoColor=white&logoSize=auto&color=%23FF4438">
  <img src="https://img.shields.io/badge/MYSQL-a?style=for-the-badge&logo=MYSQL&logoColor=white&logoSize=auto&color=%234479A1">
  <img src="https://img.shields.io/badge/REACT-a?style=for-the-badge&logo=react&logoColor=white&logoSize=auto&color=%2361DAFB">
  <img src="https://img.shields.io/badge/ROUTER-a?style=for-the-badge&logo=reactrouter&logoColor=white&logoSize=auto&color=%23CA4245">
  <img src="https://img.shields.io/badge/BOOTSTRAP-a?style=for-the-badge&logo=bootstrap&logoColor=white&logoSize=auto&color=%237952B3">
  <img src="https://img.shields.io/badge/RECOIL-a?style=for-the-badge&logo=recoil&logoColor=white&logoSize=auto&color=%233578E5">
  <img src="https://img.shields.io/badge/HTML5-a?style=for-the-badge&logo=html5&logoColor=white&logoSize=auto&color=%23E34F26">
  <img src="https://img.shields.io/badge/CSS-a?style=for-the-badge&logo=css&logoColor=white&logoSize=auto&color=%23663399">
  <img src="https://img.shields.io/badge/JAVASCRIPT-a?style=for-the-badge&logo=javascript&logoColor=white&logoSize=auto&color=%23F7DF1E">
  <img src="https://img.shields.io/badge/GIT-a?style=for-the-badge&logo=GIT&logoColor=white&logoSize=auto&color=%23F05032">
  <img src="https://img.shields.io/badge/GITHUB-a?style=for-the-badge&logo=GITHUB&logoColor=white&logoSize=auto&color=%23181717">
</div>


<br>
<br>


<br><br><br>

---


## 📝 API 명세


<br>

## 인증(Auth) 관련 API
( AuthController )

| Method | Endpoint                                        | Description                   |
|--------|-------------------------------------------------|-------------------------------|
| **GET**    | `/api/auth/me`      |  정식 사용자 인증을 위한 맵핑포인트이다. 인증이 성공적이면 유저 정보를 응답한다.              |
| **GET**    | `/api/auth/ping`    | 시큐리티 필터로 인증 상태만 가볍게 체크할 목적의 맵핑포인트이다. |
| **POST**   | `/api/auth/refresh` | jwt refresh 토큰을 이용해 access 토큰을 재발급하는 엔드포인트이다. |
| **POST**   | `/api/auth/logout`  | 엄격한 로그아웃 처리를 위한 맵핑포인트이다. 리프레시 토큰을 Redis 에서도 삭제하고, 응답으로 브라우저 쿠키에서도 리프레시 토큰을 삭제하도록 만든다. |

---

</details>

[▲개요로 스크롤](#개요)

<br><br><br><br><br>
