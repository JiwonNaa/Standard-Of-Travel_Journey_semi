<h1 style="color: #000000;"><b>STANDARD-OF-TRAVEL🏡</b></h1>
<p data-ke-size="size14">참고 사이트 - <a href="https://www.airbnb.co.kr/" target="_blank" rel="noopener&nbsp;noreferrer">https://www.airbnb.co.kr/</a></p>

<h2 style="color: #000000; text-align: start;" data-ke-size="size26"><b>😄본인 역할</b></h2>
<ul style="list-style-type: disc;" data-ke-list-type="disc">
<li><b>팀장</b></li>
<li><b>예약,결재 기능</b></li>
<li><b>리뷰 기능</b></li>
</ul>


<h2 style="color: #000000; text-align: start;" data-ke-size="size26"><b>⚙️ 개발 환경</b></h2>
<div style="background-color: #ffffff; color: #1f2328; text-align: start;">
<h4>✨ Back & Front ✨</h4>
<div style="white-space: nowrap;">
    <img src='https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white'>
      <img src='https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white'>
  <img src='https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white'>
  <img src='https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white'>
  <img src='https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white'>
    <img src='https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=Oracle&logoColor=white'>
</div>

  <h4>🛠 사용 툴 🛠</h4>
<div style="white-space: nowrap;">
  <img src='https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=for-the-badge&logo=Apache-Tomcat&logoColor=white'>
  <img src='https://img.shields.io/badge/Eclipse_Ide-2C2255?style=for-the-badge&logo=Eclipse-Ide&logoColor=white'>
  <img src='https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white'>
    <img src='https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white'>
</div>

<h4> server & library & API</h4>
<div style="white-space: nowrap;">
  <img src='https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=for-the-badge&logo=Apache-Tomcat&logoColor=white'>
  <img src='https://img.shields.io/badge/Kakao_Pay-F8DC75?style=for-the-badge&logo=kakao&logoColor=white'>
  <img src='https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=for-the-badge&logo=Apache-Tomcat&logoColor=white'>
</div>



<h2 style="color: #000000; text-align: start;" data-ke-size="size26"><b>⌨️ 담당기능</b><b></b></h2>

<h4><b>FRONT</b></h4>
<p>- reservationPayment(확인 및 결제)</p>
<p>- paymentComplete(예약확정)</p>
<p>- reservationList(예정된 예약, 지난 예약, 취소된 예약)</p>
<p>- myPage(계정)</p>
<p>- memberPersonalInfo(개인정보)</p>
<p>- loginSecurityInfo(로그인보안)</p>
<p>- 리뷰 작성, 목록, 수정 페이지</p>

<h4 data-ke-size="size20"><b>BACK</b></h4>

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


<h2 style="color: #000000; text-align: start;" data-ke-size="size26"><b>🖼️ 화면</b><b></b></h2>
<img src="README_IMG/join.png">
<img src="README_IMG/book.png">
<img src="README_IMG/review.png">
<img src="README_IMG/wish.png">
<img src="README_IMG/addAccom.png">
<img src="README_IMG/acomm.png">
<img src="README_IMG/room.png">

<h2 style="color: #000000; text-align: start;" data-ke-size="size26"><b>📝 </b><b>시장분석과 기획의도</b></h2>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">시장 트렌드와 경제적 요인을 반영하여 맞춤형 숙박 옵션을 제공했습니다. </p>
<p style="background-color: #ffffff; color: #1f2328; text-align: start;" data-ke-size="size16">또한 사용자 경험을 최적화하기 위해 직관적인 인터페이스를 제공하고, 간소화된 예약 및 결제 과정을 구현했습니다.</p>

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




<h2 style="color: #000000; text-align: start;" data-ke-size="size26"><b>📡발표 PPT</b></h2>
  https://www.canva.com/design/DAGHCWxMb14/yb3tB-bdmL8HJQ8MdQGaCg/edit?utm_content=DAGHCWxMb14&amp;utm_campaign=designshare&amp;utm_medium=link2&amp;utm_source=sharebutton

<h2 style="color: #000000; text-align: start;" data-ke-size="size26"><b>🎞시연영상</b></h2>
<p data-ke-size="size16">&nbsp;</p>
https://tv.kakao.com/v/447232382

<h2 style="color: #000000; text-align: start;" data-ke-size="size26"><b>🤓느낀점</b></h2>
<p data-ke-size="size16"><br />에어비앤비 클론코딩, 팀 프로젝트를 진행하면서 여러 가지 기술적 문제와 협력의 중요성을 깨달았습니다. 특히, 예약 관리 기능을 구현하는 과정에서 직면한 문제들은 저에게 많은 것을 배울 기회를 주었습니다.</p>
<p data-ke-size="size16">예를 들어, 비밀번호 확인 기능을 구현할 때 JSP-JS에서 데이터를 전달하는 방법을 이해하였으며, 여러 개의 리뷰 삭제 기능을 구현 할 때 Ajax를 이용한 서버 통신 방법과 JSP에서 데이터 전달 방법을 이해하게 되었습니다.</p>
<p data-ke-size="size16">예약내역을 입력하는 과정에서 클라이언트에서 받은 정보, 수정한 정보들을 재 할당? 하고 재 할당된 정보를 서버에 전달하는 과정을 경험했습니다. 또한, 예약 내역을 조회하고 리뷰 작성 여부를 확인하는 과정에서 SQL 조인과 조건문을 적절히 사용하는 방법을 익혔습니다. <br /><br />이 과정에서 팀원들과의 협력은 매우 중요했습니다.</p>
<p data-ke-size="size16">각자 맡은 부분에서 발생한 문제를 공유하고 함께 해결책을 모색하는 과정에서 팀워크의 중요성을 느꼈습니다.</p>
<p data-ke-size="size16">예를 들어, Java 서블릿에서 발생한 예외 처리 문제를 해결하는 데 도움을 주었고, 다른 팀원은 CSS와 JavaScript를 활용해 사용자 인터페이스를 개선하는 데 큰 기여를 했습니다.</p>
<p data-ke-size="size16">이러한 협력 덕분에 프로젝트의 완성도를 높일 수 있었고, 서로의 강점을 최대한 활용하는 법을 배웠습니다. <br /><br />결국,&nbsp;이번&nbsp;프로젝트를&nbsp;통해&nbsp;기술적인&nbsp;역량뿐만&nbsp;아니라&nbsp;협업&nbsp;능력도&nbsp;함께&nbsp;향상시킬&nbsp;수&nbsp;있었습니다.&nbsp;</p>
<p data-ke-size="size16">팀원들과의&nbsp;원활한&nbsp;소통과&nbsp;협력이&nbsp;없었다면&nbsp;어려운&nbsp;문제들을&nbsp;해결하는&nbsp;데&nbsp;많은&nbsp;시간이&nbsp;걸렸을&nbsp;것입니다.&nbsp;</p>
<p data-ke-size="size16">따라서,&nbsp;앞으로의&nbsp;프로젝트에서도&nbsp;팀워크를&nbsp;더욱&nbsp;중요하게&nbsp;여기고,&nbsp;지속적인&nbsp;학습을&nbsp;통해&nbsp;기술적인&nbsp;부분에서도&nbsp;성장해&nbsp;나가야겠다고&nbsp;다짐했습니다.</p>

<hr>

<p data-ke-size="size16">개인적으로는ajax를&nbsp;이용해&nbsp;서버와&nbsp;통신하는&nbsp;방법을&nbsp;연습할&nbsp;수&nbsp;있었습니다. <br />각자&nbsp;맡은&nbsp;부분에서&nbsp;발생한&nbsp;문제를&nbsp;공유하고,&nbsp;함께&nbsp;해결책을&nbsp;모색하는&nbsp;과정에서&nbsp;팀워크의&nbsp;중요성을&nbsp;느꼈습니다. <br />서로의&nbsp;강점을&nbsp;최대한&nbsp;활용해&nbsp;프로젝트의&nbsp;완성도를&nbsp;높일&nbsp;수&nbsp;있었습니다.</p>
<p data-ke-size="size16">&nbsp;</p>
<p data-ke-size="size16">&nbsp;</p>
