
<p align="center"><img src="https://github.com/user-attachments/assets/a3c38272-9c62-4a3c-8489-1cb473effb86" width="600"></p>

<br><br><br>
<h1 align="center">
   JOJO SOFT (자유주제 GUI 프로젝트)
</h1>





# Contents

## What is?

<p align="center">steam또는 다이렉트 게임즈와 같은 게임 플랫폼을 벤치마킹한 프로그램입니다.</p>
<p align="center">회원가입, 로그인, 게임구매 등 간단한 로직을 자바 swing으로 구현하였습니다.</p>




## 담당 업무 
<br>

- 회원 관련된 페이지 기능(로그인, 회원가입 등)
- 장바구니 페이지와 모의 결제기능 및 UI 구현
<br>

## 진행 과정
<br>

- 조원들이 플랫폼에 필요한 기능과 UI를 구현하여 커밋 후, 원격 저장소에 푸시하면 병합 기능을 활용하    여 팀장이 병합을 담당.
- 페어 프로그래밍 기법을 적용하여 코드를 작성하는 드라이버와 작성된 코드의 리뷰 및 논리적 오류를     찾는 내비게이터로 역할을 나누어 작업을 실시
- 연계 구현 작업과 방법은 관련 조원들이 토론하고, 결론을 다른 조원에게 공유하여 검증 작업 실시
- 작업 가시성 향상을 위해 업무 보드를 활용
<br>

## 자원 관리
<br>

- MySQL을 활용하여 유저 및 게임 데이터의 정보를 저장.
- 저장 정보가 다양해짐에 따라 효율적으로 관리하기 위해, 각 유저의 프로필 정보와 구매한 게임 정보를    외래키로 연결된 별도의 테이블로 분리하여 정규화.
- 이미지 : 이미지는 호환성을 높이고 데이터 전송 중에 발생할 수 있는 손상을 낮추기 위해 MySQL에서    이미지 모음 테이블을 생성하고 Base64를 통해 변경한 데이터로 저장.
<br>

## main Features

<br><br><br><br><br>
<p align="center"><img src="https://github.com/user-attachments/assets/cf40edaf-74ad-4426-82ef-8acf092e6ed1" width="500"></p>
<p align="center">
  MySQL user 테이블 자료의 일부분입니다.<br>
   모든 비밀번호는 직접 작성한 메소드를 통해 암호화된 상태로 데이터 베이스에 저장될 수 있도록 구성하였습니다.
</p>


<br><br><br><br><br><br>
<p align="center"><img src="https://github.com/user-attachments/assets/58a81bc6-ae9a-4da2-99fb-fec35154687d" width="500"></p>
<p align="center">
  로그인을 할 수 있는 화면입니다.
   랜덤한 확률로 광고를 넣을 수 있도록 추가 요소를 구현해보았습니다.
</p>

<br><br><br><br><br><br>
<p align="center"><img src="https://github.com/user-attachments/assets/57f7bf47-0867-4e1b-a657-bb70093c6b01" width="500"></p>
<p align="center">
  로그인에 성공했을 시 등장하는 메인화면입니다.<br>
</p>
<br><br><br>
<p>검색바 : 원하는 게임을 검색할 수 있습니다.<br></p>
<p>게임 : 미리 구성된 필터 기능을 이용하여 원하는 게임들을 찾을 수 있습니다.<br></p>
<p>프로모션 : 전체, 기본게임, DLC, 번들로 이루어진 라디오 버튼을 사용할 수 있으며 흥행 성적이 높은 순서대로 출력됩니다.<br></p>
<p>회원정보 : 자신의 닉네임, 사용금액 등등 개인정보를 알 수 있는 페이지와 구매한 게임의 코드를 확인할 수 있습니다.<br></p>
<p align="center"><img src="https://github.com/user-attachments/assets/f1eeec27-8eff-485c-979b-04f36d67ee0e" width="900"></p>
<p align="center">
<p>게임코드 또한 암호화하여 데이터 베이스에 저장하기 때문에 DB에 출력되는 문자열과 실제 문자열이 다른 것을 확인할 수 있습니다.<br></p>
<br><br><br><br><br><br>



## other components

<br><br><br><br><br><br>

<p align="center"><img src="https://github.com/user-attachments/assets/340127b3-c6a3-4ac5-9e89-ceebb73266c2" width="600"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/8c46372e-2cef-4507-bc77-0ec8f425fac7" width="600"></p>




<p align="center">
   회원가입과 회원정보 화면입니다.<br>
   회원가입은 특정한 조건(ex : 아이디는 한글 사용 x)을 만족해야 진행할 수 있도록 구현하였습니다.
</p>
<br><br><br><br><br><br>




<p align="center"><img src="https://github.com/user-attachments/assets/2ee02783-9e8d-45af-b8e2-3c1879835075" width="100" height="440"> <img src="https://github.com/user-attachments/assets/60b2f718-5414-4257-bdaf-57068d31bc5b" width="600"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/121feff0-493d-4519-ba05-533356453b40" width="600""></p>
<p align="center">
   게임 필터 화면, 게임 상세 페이지, 장바구니 화면입니다.<br>
   
</p>

<br><br><br><br><br><br>


<p align="center">
<img src="https://github.com/user-attachments/assets/a1e4cbaa-ed72-4e2a-8a0a-8ecd59241a51" width="300">
<img src="https://github.com/user-attachments/assets/47a4fba9-d9d0-4bc5-acaa-24fd4bce68fe" width="300">
</p>
<p align="center">
   금액 충전과 결제는 별도의 절차 없이 약식으로 진행할 수 있도록 구현하였습니다.<br>
</p>

<br><br><br><br><br><br>

<p align="center"><img src="https://github.com/user-attachments/assets/854634c0-5309-4e58-9f00-b889dfe491e4" width="1000"></p>



<p align="center"><img src="https://github.com/user-attachments/assets/4b109f9e-b0df-4222-89cf-f1ca92cb8ca6" width="600"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/a1cf8e1a-b645-497a-bfd6-6ae067486d98" width="600"></p>

<p align="center">
   관리자로 로그인하는 경우 게임 상품 추가와 수정을 할 수 있도록 추가 요소를 구성하였습니다.<br>
   이미지를 추가하는 경우 DB의 game_picture 테이블에 추가한 게임id와 데이터를 저장합니다.<br>
</p>


<p align="center">
  <h2>Built With</h2>
   
   Development
   <br><br>
    <img src="https://img.shields.io/badge/MySQL-005C84?logo=mysql&logoColor=white">
    <img src="https://img.shields.io/badge/Eclipse-2C2255?logo=eclipse&logoColor=white">
   <img src="https://img.shields.io/badge/GUI-2C2255?logo=eclipse&logoColor=white">
 

Enviroment
<br><br>
<img src="https://img.shields.io/badge/git-%23F05032?logo=git&logoColor=black">



## Development process

#### 역할 분배 (페어 프로그래밍 기법을 참조)


조장 : 공유 repository 생성. 프로그래밍의 방향을 설명 및 지시<br>
조원 1 : 작업할 프로젝트를 생성하고, 작업에 필요한 기본 뼈대를 구축.<br>
조원 2 : 데이터 베이스 서버 구축(권한 설정 포함), 테이블 논리 구성 및 생성.<br>

<br><br>
1. 테이블 정의 : 기본키(Pk), 외래키(Fk), 널 허용 여부(Null/Not Null), 자동 증가(Auto Increment)설정을 포함한 테이블 정의.<br>
2. 테이블 생성 : cloth, category, user등 주요 테이블 및 외래키를 구성<br>
3. ERD 논리 검증 : 테이블의 구성을 ERD 자료를 참고하여 논리 구성 오류를 체크.<br>
---
## ERD 구성

<p align="center"><img src="https://github.com/user-attachments/assets/9fd40b78-bb50-4309-9ae8-9beb4e45e949" width="700" height="600"></p>
<br>
4. PPT 자료 활용 : 구현해야하는 정보를 ppt자료를 통해 간단하게 작성한 뒤, 해당 작성 내용을 서로 공유.<br>
<br><br>
<p align="center"><img src="https://github.com/user-attachments/assets/e4b35e02-e83c-462d-97a9-855fb268cfa1" width="500" height="350"></p>
<p align="center">(요소를 클릭하면 아래와 같은 화면으로 넘어갈 수 있도록 ppt자료를 구성)</p>
<p align="center"><img src="https://github.com/user-attachments/assets/ba540d28-a587-4e9b-b0ca-3a12df96cdb2" width="500" height="350"></p>







## 자주 묻는 질문?

<h4>암호화는 어떻게 만들어서 적용했나요?</h4>

<h6>

   
   1. 변경시킬 문자열을 A라고 가정, 빈 문자열을 새로 생성하고 B라고 가정합니다.
   2. A의 첫 인덱스(i) 문자를 잘라 숫자로 변환합니다. (아스키코드 참조)
   3. 숫자를 자신이 정한 규칙대로 변경시킨 뒤 다시 문자로 변환합니다. (작성자의 경우 숫자가 0과 127이 아닐때만 1을 더하여 문자로 변경했습니다.)
   4. B에 해당 문자를 더하고 인덱스 값 (i)을 1 증가시킵니다.
   5. 1 ~ 4 번과정을 A의 문자열 길이값만큼 반복합니다.
   6. 완성된 결과를 다시 반환합니다.


게임코드를 저장하는 방법도 위의 방법을 기반으로 작성하였습니다.<br><br>
왜? : DB관리자가 유저의 비밀번호나 결제한 게임코드의 내용을 알아내는 것을 방지하고자 하는 목적으로 구현하였습니다. 
</h6>
    
## Authors

[![GitHub stats](https://github-readme-stats.vercel.app/api?username=MooHyunPark)](https://github.com/MooHyunPark)


