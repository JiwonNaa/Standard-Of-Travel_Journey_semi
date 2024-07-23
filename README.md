
# STANDARD-OF-TRAVEL_JOURNEY

TIME_지능지수
JOURNEY_여행의정석_숙박사이트

<h1 style="color: #000000;"><b>🏡여행의 정석(여정)</b></h1>
<p data-ke-size="size14">참고 사이트 - <a href="https://www.airbnb.co.kr/" target="_blank" rel="noopener&nbsp;noreferrer">https://www.airbnb.co.kr/</a></p>
<h2 style="color: #000000;" data-ke-size="size26"><b>🧑&zwj;🤝&zwj;🧑조원, 역할</b><b></b></h2>
<div style="background-color: #ffffff; color: #1f2328; text-align: start;">

  <h3>나지원 [조장 , 이슈관리자]</h3> 

<h4 data-ke-size="size20"><b>FRONT</b></h4>
<a id="user-content-front" style="color: #000000;" href="https://github.com/jisooou/Team_Journey/blob/main/README.md#front"></a></div>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- reservationPayment(확인 및 결제)</p>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- paymentComplete(예약확정)</p>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- reservationList(예정된 예약, 지난 예약, 취소된 예약)</p>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- myPage(계정)</p>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- memberPersonalInfo(개인정보)</p>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- loginSecurityInfo(로그인보안)</p>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- 리뷰 작성, 목록, 수정 페이지</p>
<div style="background-color: #ffffff; color: #1f2328; text-align: start;">
<h4 data-ke-size="size20"><b>BACK</b></h4>
<a id="user-content-back" style="color: #000000;" href="https://github.com/jisooou/Team_Journey/blob/main/README.md#back"></a></div>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- 예약 및 결제 기능 구현</p>

- 예약(게스트)
    - 날짜 수정 (날짜 변경 후 금액이 반영)
        - outDate는 inDate보다 이후, inDate는 오늘날짜 이후.
    - 인원 수정 기능
    - 목록 조회
        - 예정된 여행 
        - 취소가능, 지나간 여행 
        - 리뷰 작성가능 버튼 활성화, 작성 후 버튼 비활성화, 취소된 여행

- 결제(게스트)
    - 등록된 카드로 결제(비밀번호 유효성 검사)
        - 비밀번호 불일치 시 예약버튼 비활성화, 비밀번호 일치 시 예약버튼 활성화
    - 카카오페이로 결제 (카카오 API)
    - 결제 후 DB에 정보 등록됨

 
- 예약(호스트)
    - 예정된 예약 - 취소가능
    - 지난 예약
    - 취소된 예약
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- 리뷰 기능 구현</p>

- 리뷰
    - 작성
        - 별점 반영
        - 내용 유효성검사( 욕설 금지, 최소 10자 ~ 최대 200자)
    - 수정 - 내용 수정 가능
    - 삭제 - (한개, 여러 개, 전체 선택) 삭제 가능


<hr>
<h3>주선기[DB 관리자, 테스트 관리자]</h3>

<h4 data-ke-size="size20"><b>FRONT</b></h4>
<a id="user-content-front-1" style="color: #000000;" href="https://github.com/jisooou/Team_Journey/blob/main/README.md#front-1"></a></div>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- 숙소 상세페이지</p>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- 회원가입</p>
<div style="background-color: #ffffff; color: #1f2328; text-align: start;">
  
<h4 data-ke-size="size20"><b>BACK</b></h4>
<a id="user-content-back-1" style="color: #000000;" href="https://github.com/jisooou/Team_Journey/blob/main/README.md#back-1"></a></div>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- 호스트, 회원기능 구현</p>

- 멤버, 호스트
  - 회원 가입 - 유효성 검사(아이디 - 중복 검사/ 비밀번호- 숫자, 소문자 모두 포함 8자 이상인지 검사, 비밀 번호 일치 여부 검사)
  - 로그 인
  - 로그 아웃
  - 회원 정보 수정 - 유효성 검사 (비밀번호- 숫자, 소문자 모두 포함 8자 이상인지 검사, 비밀 번호 일치 여부 검사)
  - 회원 탈퇴 - 해당 계정으로 등록한 숙소, 객실 전부 삭제
  - 생년월일 - 회원 가입일 기준, 만 19세 이상인지 검사

<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- 객실 기능 구현</p>

- 객실
  - 객실 등록 - 유효성 검사( 객실명 - 중복 검사 )
  - 객실 수정 - 유효성 검사( 객실명 - 중복 검사 )
  - 객실 상세 페이지
      - 카카오 지도 API 사용해서 해당 객실 위치 띄우기 (숙소의 위도, 경도 사용)
      - 해당 객실의 가장 최신 후기 6개 보여주기
  - 객실 삭제

<hr>

<h3>이지수[형상관리자, 일정관리자]</h3>

<h4 data-ke-size="size20"><b>FRONT</b></h4>
<a id="user-content-front-2" style="color: #000000;" href="https://github.com/jisooou/Team_Journey/blob/main/README.md#front-2"></a></div>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- Home - header/footer</p>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- Home - 로그인</p>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- Wish - 객실관리 페이지</p>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- Wish - 위시리스트 페이지</p>
<div style="background-color: #ffffff; color: #1f2328; text-align: start;">
<h4 data-ke-size="size20"><b>BACK</b></h4>
<a id="user-content-back-2" style="color: #000000;" href="https://github.com/jisooou/Team_Journey/blob/main/README.md#back-2"></a></div>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- 숙소 기능 구현</p>

- 숙소 관리 (호스트)
    - 숙소 신규 등록
        - 각종 숙소 정보(이름, 주소, 시설 여부, 위도/경도, 이미지)를 입력.
    - 숙소 관리
        - 숙소 상세보기
        - 수정과 삭제 기능 
        (이후 숙소-객실 관리가 연결되도록 구현)

<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- 위시리스트 기능 구현</p>

- 홈페이지에서 객실 찜 기능 구현 (멤버)
    - 위시리스트에서 해당 정보 확인 가능.
    - 위시리스트에서 찜 삭제 및 해당 객실로 상세보기 이동 가능.

<hr>
<h2 style="color: #000000; text-align: start;" data-ke-size="size26"><b>📝 </b><b>시장분석과 기획의도</b></h2>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">시장 트렌드와 경제적 요인을 반영하여 맞춤형 숙박 옵션을 제공했습니다. </p>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">또한 사용자 경험을 최적화하기 위해 직관적인 인터페이스를 제공하고, 간소화된 예약 및 결제 과정을 구현했습니다.</p>
<h2 style="color: #000000; text-align: start;" data-ke-size="size26"><b>🔖 주요기능</b><b></b></h2>
<img src="README_IMG/join.png">
<img src="README_IMG/book.png">
<img src="README_IMG/review.png">
<img src="README_IMG/wish.png">
<img src="README_IMG/addAccom.png">
<img src="README_IMG/acomm.png">
<img src="README_IMG/room.png">

<h2 style="color: #000000; text-align: start;" data-ke-size="size26">🎛️UML 다이어그램</h2>
<img src="README_IMG/UML.png">

<h2 style="color: #000000; text-align: start;" data-ke-size="size26"><b>🗃️ERD</b></h2>
<img src="README_IMG/ERD.png">

<h2 style="color: #000000; text-align: start;" data-ke-size="size26"><b>📅개발 일정</b></h2>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">[ week1 ] 주제회의 및 기획 &amp; DB모델링</p>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">[ week2 ] DB모델링 수정 보완</p>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">[ week3 ] UI 설계 및 구형</p>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">[ week4 ] UI 수정 보완</p>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">[ week5 ] 백엔드 설계 및 구현</p>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">[ week6 ] 백엔드 디버깅 및 PPT작성 &amp; 발표 준비</p>

<img src="README_IMG/schedule.png">

<h2 style="color: #000000; text-align: start;" data-ke-size="size26"><b>⚙️ 개발 환경</b></h2>
<div style="background-color: #ffffff; color: #1f2328; text-align: start;">
<h3 data-ke-size="size23"><b>BACK</b></h3>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- `자바`, `DB(SQL)`, `톰캣`</p>
<div style="background-color: #ffffff; color: #1f2328; text-align: start;">
<h3 data-ke-size="size23"><b>Front</b></h3>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- `JSP`, `CSS`, `JQuery`, `피그마`</p>
<div style="background-color: #ffffff; color: #1f2328; text-align: start;">
<h3 data-ke-size="size23"><b>협업</b></h3>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- `깃허브`, `노션`</p>
<div style="background-color: #ffffff; color: #1f2328; text-align: start;">
<h3 data-ke-size="size23"><b>API</b></h3>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">- `Kakao Pay`, `Kakao Map`</p>
<h2 style="color: #000000; text-align: start;" data-ke-size="size26"><b>📡발표 PPT</b></h2>
  https://www.canva.com/design/DAGHCWxMb14/yb3tB-bdmL8HJQ8MdQGaCg/edit?utm_content=DAGHCWxMb14&amp;utm_campaign=designshare&amp;utm_medium=link2&amp;utm_source=sharebutton
<p data-ke-size="size16">&nbsp;</p>
<h2 style="color: #000000; text-align: start;" data-ke-size="size26"><b>🎞시연영상</b></h2>
<p data-ke-size="size16">&nbsp;</p>
https://tv.kakao.com/v/447232382
<figcaption style="display: none;"></figcaption>
</figure>
<p data-ke-size="size16">&nbsp;</p>
<p style="color: #333333; text-align: start;" data-ke-size="size16">&nbsp;</p>
<hr data-ke-style="style6" data-ke-type="horizontalRule" />
<h2 style="color: #000000; text-align: start;" data-ke-size="size26"><b>😄본인 역할&nbsp;</b></h2>
<ul style="list-style-type: disc;" data-ke-list-type="disc">
<li><b>조장</b></li>
<li><b>이슈관리자</b></li>
</ul>
<p data-ke-size="size16">&nbsp;</p>
<hr contenteditable="false" data-ke-type="horizontalRule" data-ke-style="style6" />
<h2 style="color: #000000; text-align: start;" data-ke-size="size26"><b>🤓느낀점</b></h2>
<p data-ke-size="size16"><br />에어비앤비 클론코딩, 팀 프로젝트를 진행하면서 여러 가지 기술적 문제와 협력의 중요성을 깨달았습니다. 특히, 예약 관리 기능을 구현하는 과정에서 직면한 문제들은 저에게 많은 것을 배울 기회를 주었습니다.</p>
<p data-ke-size="size16">예를 들어, 비밀번호 확인 기능을 구현할 때 JSP-JS에서 데이터를 전달하는 방법을 이해하였으며, 여러 개의 리뷰 삭제 기능을 구현 할 때 Ajax를 이용한 서버 통신 방법과 JSP에서 데이터 전달 방법을 이해하게 되었습니다.</p>
<p data-ke-size="size16">예약내역을 입력하는 과정에서 클라이언트에서 받은 정보, 수정한 정보들을 재 할당? 하고 재 할당된 정보를 서버에 전달하는 과정을 경험했습니다. 또한, 예약 내역을 조회하고 리뷰 작성 여부를 확인하는 과정에서 SQL 조인과 조건문을 적절히 사용하는 방법을 익혔습니다. <br /><br />이 과정에서 팀원들과의 협력은 매우 중요했습니다.</p>
<p data-ke-size="size16">각자 맡은 부분에서 발생한 문제를 공유하고 함께 해결책을 모색하는 과정에서 팀워크의 중요성을 느꼈습니다.</p>
<p data-ke-size="size16">예를 들어, Java 서블릿에서 발생한 예외 처리 문제를 해결하는 데 도움을 주었고, 다른 팀원은 CSS와 JavaScript를 활용해 사용자 인터페이스를 개선하는 데 큰 기여를 했습니다.</p>
<p data-ke-size="size16">이러한 협력 덕분에 프로젝트의 완성도를 높일 수 있었고, 서로의 강점을 최대한 활용하는 법을 배웠습니다. <br /><br />결국,&nbsp;이번&nbsp;프로젝트를&nbsp;통해&nbsp;기술적인&nbsp;역량뿐만&nbsp;아니라&nbsp;협업&nbsp;능력도&nbsp;함께&nbsp;향상시킬&nbsp;수&nbsp;있었습니다.&nbsp;</p>
<p data-ke-size="size16">팀원들과의&nbsp;원활한&nbsp;소통과&nbsp;협력이&nbsp;없었다면&nbsp;어려운&nbsp;문제들을&nbsp;해결하는&nbsp;데&nbsp;많은&nbsp;시간이&nbsp;걸렸을&nbsp;것입니다.&nbsp;</p>
<p data-ke-size="size16">따라서,&nbsp;앞으로의&nbsp;프로젝트에서도&nbsp;팀워크를&nbsp;더욱&nbsp;중요하게&nbsp;여기고,&nbsp;지속적인&nbsp;학습을&nbsp;통해&nbsp;기술적인&nbsp;부분에서도&nbsp;성장해&nbsp;나가야겠다고&nbsp;다짐했습니다.</p>
<p data-ke-size="size16">&nbsp;</p>
<p data-ke-size="size16">&nbsp;</p>
<hr contenteditable="false" data-ke-type="horizontalRule" data-ke-style="style1" />
<p data-ke-size="size16">&nbsp;</p>
<p data-ke-size="size16">&nbsp;</p>
<p data-ke-size="size16">개인적으로는ajax를&nbsp;이용해&nbsp;서버와&nbsp;통신하는&nbsp;방법을&nbsp;연습할&nbsp;수&nbsp;있었습니다. <br />각자&nbsp;맡은&nbsp;부분에서&nbsp;발생한&nbsp;문제를&nbsp;공유하고,&nbsp;함께&nbsp;해결책을&nbsp;모색하는&nbsp;과정에서&nbsp;팀워크의&nbsp;중요성을&nbsp;느꼈습니다. <br />서로의&nbsp;강점을&nbsp;최대한&nbsp;활용해&nbsp;프로젝트의&nbsp;완성도를&nbsp;높일&nbsp;수&nbsp;있었습니다.</p>
<p data-ke-size="size16">&nbsp;</p>
<p data-ke-size="size16">&nbsp;</p>
