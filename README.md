# 3조 서버 프로그램 구현 ( BOOK SERVICE )

# 조원 👥
- 이재용
- 배주현
- 김준영

# STACKS 😶‍🌫️
- **프론트엔드** : <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/JAVASCRIPT-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white">, JSP
- **백엔드** : <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
- **DB** : <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white"> MYBATIS

# 주요 기능
- 도서 대여, 대여 목록 조회, 반납, 반납일 연장 기능
- 도서 회원 가입(회원등록), 회원 정보 조회, 회원 정보 수정, 회원 정보 삭제

# 도서 대여 기능
## 도서 대여
---
**엔드포인트 : ("/lend/add")**

![image](https://github.com/user-attachments/assets/02d8d8fc-75a9-4ee0-b1fe-a61ffc6efdba)

<hr>

## 대여 목록 조회
---

**엔드포인트 : ("/lend/list")**

![image](https://github.com/user-attachments/assets/a057456f-7c1d-4afc-afa3-61b023544222)

<hr>

## 반납
---

**엔드포인트 : ("/lend/bookReturn")**

![image](https://github.com/user-attachments/assets/16398d30-5ad0-427a-af72-d743830e3512)

<hr>

## 반납일 연장
---

**엔드포인트 : ("/lend/day")**

![image](https://github.com/user-attachments/assets/726b01bb-053b-4fbf-b046-6e1a5e44d9e9)

<hr>

# 도서 회원 관리 기능

## 회원 가입
---

**엔드포인트 : ("/user/register")**
![image](https://github.com/user-attachments/assets/32c65a78-f4cb-4968-816d-e4cd0029bf39)

<hr>

## 회원 목록 페이지에서 조회, 수정, 삭제
---

**엔드 포인트 : ("/user/list") 로 접속 해 회원 목록 조회,수정과 삭제가 동시에 가능**


![image](https://github.com/user-attachments/assets/85fd5e90-f0c4-4217-997a-b3dc6e8d039a)

⬆️ 회원 목록 페이지

<hr>

![image](https://github.com/user-attachments/assets/997ae754-766e-4fe7-a6c4-db78dad6bd67)

⬆️ 회원 목록 페이지 에서 선택 수정, 삭제

<hr>

![image](https://github.com/user-attachments/assets/8b6537d7-f83e-4b59-bfa8-56afb9f10232)

⬆️ JSP 코드

<hr>

## 회원 정보 수정
---

**엔드포인트 : ("/user/edit")**
![image](https://github.com/user-attachments/assets/c131b080-1f17-447c-9028-1352ab3dc213)

<hr>


