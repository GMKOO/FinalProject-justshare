# SpringBoot-Project-Just Share
스프링 부트 + JSP 

사용자간 직거래 공간 공유 플랫폼



## 🖥️ 프로젝트 소개
고객들이 직접 공간 제공자와 사용자로 참여하는 직거래 플랫폼 

예)를 들어 당근마켓에 지역 및 위치 기반, 개인간 소통에 장점과 에어비앤비에 Share (공간 공유 및 재임대) 아이디어를 활용함.
<br>

## 🕰️ 개발 기간
* 23.10.11일 - 23.11.19일

### 🧑‍🤝‍🧑 맴버구성
 
 - 팀장 :  관모 - 웹소켓을 활용해 실시간 채팅 및 알림 기능, 거래 기능 구현
 - 팀원 :  대규  
 - 팀원 :  재윤
 - 팀원 :  상민
 - 팀원 :  종휘

### ⚙️ 개발 환경
- `Java 11`
- **Framework** : 전자 정부 프레임워크 Springboot(2.x)
- **Database** : mysql 8.0
- **ORM** : Mybatis
- 참여 기업 프로젝트에 맞춰서 반응형 웹 픽셀 5 기준으로 개발함
- https://github.com/JY015/JustShare 개발기간 동안 git 활용하여 팀원과 협업

## 📌 개인 주요 기능 

#### 실시간 채팅 기능 - <a href="https://github.com/GMKOO/FinalProject-justshare/blob/master/JustShare/src/main/webapp/WEB-INF/view/chat1.jsp" >상세보기 - 이동</a> 
- 게시물 거래하기를 통해 판매자와 실시간 채팅 및 대화 목록 리스트 에서 이전 상대와 최근 마지막 대화 및 시간 표시
- 사용자별 대화 목록 리스트 Ajax를 활용해 실시간 사용자 검색기능
- 대화방 나가기 기능, 차단 기능
- sock.js 활용해 MPA에 단점인 페이지 이동시 소켓 끊김을 사용자가 못느끼게 개발함.
- socket.js파일을 만들어 footer에 넣고 모든 페이지 웹소켓 연결 및 페이지별 기능 별도 구현 socket.js, socket2.js 등
- 채팅 페이지는 jsp에서 CSR방식으로 동적생성을 통해 SPA로 구성함. 채팅목록리스트 및 채팅방
- chat1.jsp , java.chat 폴더 , socket.mapper 
  
#### 알림 기능 - <a href="https://github.com/GMKOO/FinalProject-justshare/blob/master/JustShare/src/main/webapp/WEB-INF/view/chat1.jsp" >상세보기 - 이동</a>
- 사용자와 첫 대화시 신규 메세지 알람 팝업 - 클릭시 대화 목록 리스트로 이동
- 거래요청 알람 팝업 -클릭시 거래화면으로 이동
- 거래완료 알람 팝업 -클릭시 리뷰작성으로 이동
- 대화목록리스트에서 사용자별 읽지 않은 신규 메세지 count 기능
- footer에 모든 사용자에 읽지 않은 신규 메세지 합산 count 기능
- 대화 사용자 접속여부 실시간 확인 및 실시간 업데이트 기능 online,offline 실시간 반영
- 토스트 라이브러리 활용
- chat1.jsp, java.chat 폴더 , socket.mapper 


## ✨ 주요 이미지

<img width="310" alt="첫대화시 알람" src="https://github.com/GMKOO/FinalProject-justshare/assets/130493398/7d361dee-7f4c-45b4-951f-97f76ee9204f">
<br>
<img width="306" alt="페이지상관없이 알람" src="https://github.com/GMKOO/FinalProject-justshare/assets/130493398/a331e215-0dd7-40ac-8462-b8a8314b2a14">
<br>
<img width="195" alt="채팅목록리스트" src="https://github.com/GMKOO/FinalProject-justshare/assets/130493398/07e97632-6cde-467b-8974-4bbfff3f02dc">
<br>
<img width="195" alt="대화시작2" src="https://github.com/GMKOO/FinalProject-justshare/assets/130493398/5775a839-6242-443c-937e-b2adf6aaa6a4">
<br>
<img width="235" alt="키도 화면" src="https://github.com/GMKOO/FinalProject-justshare/assets/130493398/4f7701b0-d1fc-43b6-9bb1-672cb393228c">
<br>
<img width="311" alt="클릭시 호스트 사용자 둘다 확인요청" src="https://github.com/GMKOO/FinalProject-justshare/assets/130493398/82698fb3-ea4c-4a7b-a695-c2cc482e447d">
<br>
<img width="196" alt="거래하기버튼" src="https://github.com/GMKOO/FinalProject-justshare/assets/130493398/d7d6928f-3ef7-4808-ad8b-b308f22c0a76">
<br>
<img width="312" alt="대화나가기 차단하기" src="https://github.com/GMKOO/FinalProject-justshare/assets/130493398/0fbe354a-ae0c-48a1-8f0c-acc19d4597e1">
<br>

## 🎞 개인 파트 시연 영상

-신규 메세지 알림 및 거래 기능
https://github.com/GMKOO/FinalProject-justshare/assets/130493398/01bd2449-1256-402c-88db-7aec13302e76
<br>

-실시간 접속 online,offline 업데이트 기능
https://github.com/GMKOO/FinalProject-justshare/assets/130493398/ce977307-d1f0-44f4-8916-87d9887d8030
<br>

-메세지 카운트 기능 및 거래 완료 기능
https://github.com/GMKOO/FinalProject-justshare/assets/130493398/4acfad48-d1e6-4be0-b477-92870376f52b
<br>

-차단기능
https://github.com/GMKOO/FinalProject-justshare/assets/130493398/2e0c75b9-acb0-4c35-b35a-8b139d7e546d
<br>

-차단해제 기능
https://github.com/GMKOO/FinalProject-justshare/assets/130493398/36232820-e5f6-4bd9-858e-236ca2f0b1c2
<br>














