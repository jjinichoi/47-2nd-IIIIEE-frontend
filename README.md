# Project IIIIEE
<p align="center"><img src="https://github.com/wecode-bootcamp-korea/47-2nd-IIIIEE-backend/assets/131442242/dd857a7d-8799-4377-b5ce-7364d624f668" width="500"/></p>

#### \*[AirBnB](https://www.airbnb.com/) 웹사이트를 모델링한 프로젝트입니다.

## 📚 기술 스택
### Frontend
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/html-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/styledcomponents-DB7093?style=for-the-badge&logo=styledcomponents&logoColor=white"> <img src="https://img.shields.io/badge/eslint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white"> <img src="https://img.shields.io/badge/prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=black">
### Backend
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/nodedotjs-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"> <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">

## ⚙️ 협업툴
<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white"> <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"> <img src="https://img.shields.io/badge/trello-0052CC?style=for-the-badge&logo=trello&logoColor=white"> <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white"> <img src="https://img.shields.io/badge/visualstudiocode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white">

## 🐱 개발 기간 및 인원

- 개발 기간 : 2023/07/14 ~ 2023/07/28
  
- 개발 인원 : 프론트엔드 2명 , 백엔드 4명
  - FrontEnd : 최진이, 양회진
  - Backend : 신동현, 최리나, 김상원, 정성남

- 깃헙 레포지토리
  - [Frontend](https://github.com/wecode-bootcamp-korea/47-2nd-IIIIEE-frontend)
  - [Backend](https://github.com/wecode-bootcamp-korea/47-2nd-IIIIEE-backend)

## 💡 서비스 소개
- 서비스명 : 맛나는 맛남
- 판매상품 : 맛집 탐방을 취미로 즐기는 사람들을 연결해주는 커뮤니티
- End_User : 홀로 맛집을 가고 싶지 않으며, 사람들과 함께 가고 싶어하는 유저들. 다양한 인맥을 넓히고자 모임을 원하는 사람들. 
- Products :
  - 누구나 주최자 (host) / 고객 (geust)가 될 수 있다는 것
  - 원하는 맛집을 호스트가 주최하고, 게스트가 직접 참여할 수 있도록 하며, 호스트와 게스트는 서로 만남을 가짐과 동시에 맛있는 음식을 먹으며 대화를 하며 친목을 다질 수 있다.
  - 맛집 탐방을 취미로 즐기는 사람들을 연결해주는 커뮤니티
  - 해당 커뮤니티와 자사 서비스를 사용하는 파트너 식당의 중개 역할
  - 방을 만들고 예약 할 때 수수료를 받고 있음. 
  - 방 만들때 받는 수수료는 우리가 가져가고 예약금은 파트너 식당으로 넘어감.
  - 수익 창출은 방 수수료 및 파트너사를 통하여 진행.
  - 예약금은 식당을 위한 노쇼 방지로 활용 됨.
    
## 💻 구현한 사항
- 회원가입/ 로그인/ 로그아웃 : 카카오 Login API 사용하여 로그인한 유저 정보 가져옴/ 로그아웃 시 토큰 삭제
- 메인페이지 맛집 필터링 기능 : 유저가 선택한 자치구, 날짜, 시간, 연령대, 나이대에 따라 맛집목록 필터링
- 맛집정보 페이지 : 카카오 map API 사용하여 맛집이 어디 위치해 있는지 정보제공, 슬라이드를 이용하여 맛집 대표이미지 노출
- 예약하기(결제) : 카카오페이 API 사용하여 맛집예약금을 결제하기
- 별점 및 후기 구현 : 만남 이후 host에 대한 별점 및 후기를 남길 수 있음(중복작성 불가)
- 모임등록 : 유저가 host가 되어 원하는 조건에 맞는 geust들을 신청받을 수 있는 방 생성 기능
- 신청하기 : geust입장의 유저가 모임 신청 시 모임정보에 신청정보를 넘겨줌


## ⚙️ 시연 영상
[![Video Label](http://img.youtube.com/vi/rx7zdgdbR0s/0.jpg)](https://youtu.be/rx7zdgdbR0s)

## 🛠 내가 기여한 사항
### 페이지 레이아웃 구성 및 구현

### 카카오로그인 API를 사용한 회원가입 / 로그인 기능
- REDIRECT_URI를 통해 카카오한테 인가코드를 받아서 back한테 넘겨준다음 back에서 카카오토큰을 받아온 후 우리 서버 토큰을 발행 한것을 GET요청 후 
  유저가 사이트를 이용할 수 있도록 화면전환 기능 구현
- 인증 완료된 고객이 페이지 이동 시 매번 로그인 수고를 덜 수 있도록, Local Stroage에 토큰 저장 방식 적용
- 토큰여부 확인 후 토큰이 없는 유저가 private페이지 접근 시 카카로 로그인 페이지로 이동 기능 구현
- 로그인페이지 이동 전 잠깐의 화면노출을 방지하기 위해 loading을 띄어줌
- REDIRECT_URI, KAKAO_REST_API_KEY는 .env파일로 관리

### 메인페이지 맛집 필터링 기능
- UI/UX적 관점에서 조건별 맛집목록을 볼 수 있는 모달창 구현
- 유저가 선택한 자치구, 날짜, 시간, 연령대, 나이대에 따라 Query String에 값을 넣어줌
- useSearchParams를 사용하여 Query String에 값을 확인 후 필터링된 맛집 목록을 GET요청

### 카카오맵 API를 사용한 맛집 상세 페이지 구현
- 메인에서 유저가 맛집을 클릭 시 GET요청하여 맛집 정보 노출
- 모바일 페이지로 구성된만큼 UI/UX적 관점에서 맛집 대표 이미지들을 슬라이드로 구현(slick)
- GET으로 받아온 좌표를 이용하여 지도에 맛집 위치를 커스텀한 Maker로 표시
- KAKAO_JS_KEY는 .env파일로 관리

### Geust 신청 목록 페이지 기능 구현
- 

  

## 📑 참고자료

Trello - Ticket management</br>
https://trello.com/b/HrqeM69z/iiiiee

ERD</br>
https://drawsql.app/teams/lena-4/diagrams/-3

