
<p align="center"><img src="https://github.com/user-attachments/assets/a3c38272-9c62-4a3c-8489-1cb473effb86" width="600"></p>

<br><br><br>
<h1 align="center">
   JOJO SOFT (자유주제 swing 프로젝트)
</h1>





# Contents

## What is?

<p align="center">steam또는 다이렉트 게임즈와 같은 게임 플랫폼을 벤치마킹한 프로그램입니다.</p>
<p align="center">회원가입, 로그인, 게임구매 등 간단한 로직을 자바 swing으로 구현하였습니다.</p>






## Key Features

<br><br>

### 회원 정보 관리

<br><br><br><br><br><br>
<p align="center"><img src="https://github.com/user-attachments/assets/cf40edaf-74ad-4426-82ef-8acf092e6ed1" width="700"></p>
<p align="center">
  MySQL user 테이블 자료의 일부분입니다.<br>
   모든 비밀번호는 직접 작성한 메소드를 통해 암호화된 상태로 데이터 베이스에 저장될 수 있도록 구성하였습니다.
</p>


<br><br><br><br><br><br>
<p align="center"><img src="https://github.com/user-attachments/assets/58a81bc6-ae9a-4da2-99fb-fec35154687d" width="700"></p>
<p align="center">
  로그인을 할 수 있는 화면입니다.
   랜덤한 확률로 광고를 넣을 수 있도록 추가 요소를 구현해보았습니다.
</p>

ex : 기존의 쇼핑몰 필터 예제
<br><br><br>
<p align="center"><img src="https://github.com/user-attachments/assets/2a74e63f-db82-47b3-92e6-2039a6c05a23" width="800"></p>
<br><br>

ex : 변경한 쇼핑몰 필터 예제 (어려운 단어 사용을 최대한 배제. 색깔, 계절 등의 정보를 바탕으로 결과목록을 추천)
<br><br><br>
<p align="center"><img src="https://github.com/user-attachments/assets/0a578e91-fd4a-4239-904b-63d3db4141a4" width="500"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/1754e607-5d0d-460f-86f9-c9bb1dba09db" width="500"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/d6648599-f051-4c73-9602-8317c2e0d115" width="500"></p>

## other components

<br><br>
<p align="center">제품을 클릭하였을 때 구매자들의 평가를 쉽게 알 수 있도록 요소 배치 (좋아요, 싫어요)</p>
<br><br>

<p align="center"><img src="https://github.com/user-attachments/assets/497e56d0-69de-499e-b7b1-69615b2435e3" width="700></p>
<p align="center"><img src="https://github.com/user-attachments/assets/b2d59862-7f8c-42d0-b0c6-583d4b8e3002" width="700"></p>
<br><br><br><br>

<p align="center">주소, 결제 등의 요소들은 타 사이트의 api를 이용하여 구현</p>
<br><br>
<p align="center"><img src="https://github.com/user-attachments/assets/68803700-d5db-4d21-a50c-c648a32d17fb" width="500"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/4d79da3d-85a0-4bc9-95c9-4b2a439cc84c" width="500"></p>
<br><br><br><br>

<p align="center">그 외 쇼핑몰 이용에 필요한 서브 기능</p>
<p align="center"><img src="https://github.com/user-attachments/assets/dd1afe3b-f106-4670-a532-2a9aa74b5c56" width="1000"></p>
<p align="center"><img src="https://github.com/user-attachments/assets/774adc3a-7859-492a-a416-9b0624c1c183" width="1000"></p>






<p align="center">
  <h2>Built With</h2>
   
   Development
   <br><br>
    <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white">
    <img src="https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipse&logoColor=white">
    <img src="https://img.shields.io/badge/javascript-%23F7DF1E?logo=javascript&logoColor=black">
    <img src="https://img.shields.io/badge/html-%23E34F26?logo=html5&logoColor=black">
 

Enviroment
<br><br>
<img src="https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white">
<img src="https://img.shields.io/badge/apachetomcat-%23F8DC75?logo=apachetomcat&logoColor=black">
<img src="https://img.shields.io/badge/git-%23F05032?logo=git&logoColor=black">



## Development setup

데이터베이스 서버 구축(권한 설정 포함), 테이블 논리 구성, 작업 프로젝트 생성, 공유 repository 생성 등 역할을 분배하여 개발환경을 구축.

1. 테이블 정의 : 기본키(Pk), 외래키(Fk), 널 허용 여부(Null/Not Null), 자동 증가(Auto Increment)설정을 포함한 테이블 정의.
2. 테이블 생성 : cloth, category, user등 주요 테이블 및 외래키를 구성
3. ERD 활용 : 엔터티-관계 다이어그램을 기반으로 테이블 간의 외래키 관계를 검증하여 데이터베이스의 무결성 유지
4. Test Mapper를 작성하여 실시간 입출력 테스트

---
## ERD 구성

<img src="https://github.com/user-attachments/assets/6552cbfa-4483-448d-a442-34efdb730dc2" width="1000" height="1000">

---


## collaboration process
<br><br>
<p align="center"><img src="https://github.com/user-attachments/assets/79768f31-04f3-41b7-87d8-c68c1abd4857" width="1000"></p>
<br><br><br><br>
<p align="center">각 요소들의 설계 초안을 ppts 파일을 이용하여 부가 설명 진행</p>
<br><br>
<p align="center"><img src="https://github.com/user-attachments/assets/170dd687-22e0-4b12-b998-4bc0c42e981f" width="1000"></p>
<br><br><br><br>



## 자주 묻는 질문?

<h4>설문조사필터기능의 알고리즘은 어떤 방식으로 작동하나요?</h4>

<h6>카테고리 테이블은 상품들의 id값을 외래키로 참조하고 있으며 나머지 컬럼들은 세부 카테고리 테이블들의 값을 가지고 있습니다. (계절, 색깔, 상하의등)
  이를 이용하여 설문결과를 바탕으로 특정한 숫자값을 가져온 뒤, 세부 카테고리에 숫자값이 포함되어 있는 모든 옷들을 select 문으로 찾습니다.
     
   ex(계절) : 봄 = 1 여름 = 2 가을 = 3 겨울 = 4 모든계절 = 5 라고 가정하고,
   봄을 선택하였다면 카테고리 테이블의 season_category 값이 1 또는 5인 모든 옷을 where 절로 찾습니다.
</h6>
    
## Authors

[![GitHub stats](https://github-readme-stats.vercel.app/api?username=MooHyunPark)](https://github.com/MooHyunPark)


