## 📔 프로젝트 이름

- 인스타그램_클론코딩

---

# 💎 클론코딩 프로젝트 소개

- 인스타그램에 있는 기능들을 하나하나 구현하는 방식으로 하였습니다.

---

## 📆 개발기간

2022.03.03 ~ 2022.03.09
 
---

## 📔 노션 사이

https://www.notion.so/6-9286f512bafd43a3ac152ee3357f0a12

---

## 🛠️ 기술스택

- FE

    <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black">
    <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=Redux&logoColor=white">
    <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=white">
    <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=Bootstrap&logoColor=white">
    
- BE
    
    <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white">
    <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=white">
    <img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=Gradle&logoColor=white">
    <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
    <img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=for-the-badge&logo=Amazon EC2&logoColor=white">
    <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white">
    <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=black">
    
    
---   

## 💡 구현기능
   
   - 로그인 기능
     - 유효성 검사를 통과한 ID, PW인 경우만 회원가입이 가능하다.
     - JWT 토큰을 이용하여 Spring Secuity로 인증/인가를 구현한다.
   - 게시물 등록
     - 로그인을 하면 게시물을 등록할 수 있다.
     - 본인이 작성한 게시물만 수정/삭제가 가능하다.
   - 게시물 조회
     - 모든 사용자가 작성한 게시물를 조회할 수 있다.
     - 작성일자, 좋아요 개수 순으로 정렬할 수 있다.
   - 마이페이지 조회
     - 내가 작성한 게시물을 볼 수 있다.
   - 댓글 등록
     - 게시물에 댓글을 달 수 있다.
     - 본인이 작성한 댓글만 수정/삭제가 가능하다.
   - 좋아요 기능
     - 게시물, 댓글에 좋아요를 누를 수 있다.
     - 이미 좋아요를 누른 상태에서 다시 한번 누르면 좋아요가 취소된다.

---

## 🎬 시연영상

---

## 📋 와이어 프레임

- Login
    
    ![스크린샷 2023-03-03 오전 11 31 54](https://user-images.githubusercontent.com/121671967/223946881-df740d13-ce44-4b6d-9f8f-5b60cfd1e48f.png)

    
    
- signup
    
    
    ![스크린샷 2023-03-03 오전 11 31 35](https://user-images.githubusercontent.com/121671967/223946907-5f1b0989-6732-4dee-8661-ca7373c536c4.png)

    
- Main
    
    ![Untitled](https://user-images.githubusercontent.com/121671967/223947005-28f2e388-0be5-4760-a71e-5e3d30e44035.png)

    
- Main-Add Page
    
    ![Untitled (1)](https://user-images.githubusercontent.com/121671967/223947071-adf907ff-21b0-4f66-87e5-54a51d53b376.png)
    ![Untitled (2)](https://user-images.githubusercontent.com/121671967/223947085-877e6007-0b89-4c5b-9e2e-82ee1f56a4ff.png)

    
- Modal
    
    ![Untitled (3)](https://user-images.githubusercontent.com/121671967/223947122-6bd48ea8-0b94-43d8-95e1-80f6313129e5.png)
 
---

## 📄 ERD

<img width="1496" alt="image" src="https://user-images.githubusercontent.com/121671967/223958067-b9b92923-5c89-4b09-8c34-4c92bc9cd08f.png">


---

## 📜 API 문서

![API 명세서](https://user-images.githubusercontent.com/121671967/223951097-ca91acbb-93e7-4db3-b2ff-bb3c3608adbb.png)
   
---

## 👥 조원 정보
|이름|  구분   |        업무파트        |           Github 주소           |
|:---:|:-----:|:------------------:|:-----------------------------:|
|이승렬|  백엔드  | 이미지, 좋아요, S3 기능, 서버 배포  |  https://github.com/LEESEUNGRYEOL |
|조민성|  백엔드  | 회원가입, 로그인, JWT TOKEN |  https://github.com/Ganpyeon  |
|홍예석|  백엔드  | 게시굴, 댓글, SWAGGER, 무한 스크롤 | https://github.com/yshong1998 |
|백주원| 프론트엔드 | 로그인, 회원가입, 메인 페이지, 모달  |  https://github.com/baekjoowon  |
|이주애| 프론트엔드 | 마이 페이지 | https://github.com/leejuae1020 |
