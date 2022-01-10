# WEB1_HTML
생활코딩/ Egoing

2021.12.03~



-12/3

      web1-1 Html& Internet

      web1-2 프로젝트의 동기

      web1-3 기획

-12/4

       GitHUB Atom 연동(성공)

       web1-4 코딩과 HTML

       web1-5 HTML 코딩 실습 환경 준비


-12/5

       web1-6 기본문법 -태그

       <strong></strong>(글씨 강조)
       <u></u>(밑줄)

       web1-7 혁명적인 변화

        <h1>-<h6>까지 있고 h1일때 글씨가 젤 크고 숫자가 클수록 글씨가 작다, 줄바꿈 가능)

        web1-8 통계에 기반한 학습

        web1-9 줄바꿈

        <br> 태그는 태그를안닫는다 그저 줄바꿈
        <p></p> 태그는 단락을 표현하기 좋고 웹페이지 정보로서 가치있게
        해줌. <br>은 자유롭고 <p>태그는 자유도가 시각적으로 떨어짐


  -12/27  

         web1-10 html이 중요한 이유


         누구나 차별없이 정보에 접근할 수 있어야 한다.

         web1-11 최후의 문법 속성과 img

         사진 넣기
         =<img src="" width="">

         web1-12 부모 자식과 목록

         <li><li> = 목록 만들기
         다른 목록과 구분할 수 있도록 경계만들기=<ul>
         많은 목록 수정시 번거러움을 없애주는 =<ol>

         web1-13 문서의 구조와 슈퍼스타들

         <tittle> <tittle> 웹페이지 제목 변경
         영어아닌 문자가 깨지는경우 <meta charset="utf-8">
         본문은 <body> </body> 본문을 설명하는 태그는<head> </head>
         body와 head를 감싸는 태그는 <html>
         웹페이지가 html로 만들어졌다는 것을 표현하기 위한
         <!doctype html> 코드

  -12/28


        web1-14 HTML 태그의 제왕
        <a></a>태그 링크 걸기

        web1-15 웹사이트 완성.(web 사이트 만들어보기)





   -12/30

          web1-16 원시웹

          web1-17 인터넷을 여는 열쇠:서버와 클라이언트

          web1-18 웹 호스팅(GitHUB)

          web1-19 웹서버 운영하기







-12/31




            web1-19.1
            웹서버 설치

            web1-19.2
            웹서버와 http

            web1-19.3
            웹브라우저와 웹서버의 통신

            web1-20.1
            수업을 마치며1/3




-01/03

              web1-20.2
              수업을 마치며2/3

              web1-20.3
              수업을 마치며3/3
              CSS → web publisher, web designer
              JavaScript → web front end engineer, web interactive designer
              JSP, PHP, Node.js → back end

              web1- 부록 코드의 힘
              동영상 삽입

              web1-부록 코드의 힘
              댓글 기능 추가



-01/04


            web1-부록 코드의 힘
            채팅기능 추가

            web1-부록 코드의 힘
            방문자 분석기

            -html 복습-

            클라이언트 - 기술소개

            클라이언트- 기본문법1,2
            <strong>은 글씨강조 </strong>으로 닫아주기
            시작태그              닫히는태그
            <h1></h1> 제목1 이라는 뜻 숫자가 클수록 글씨가 작음
          h 태그는 <h1>~<h6>까지 있다.


-01/05


          클라이언트- 하이퍼 텍스와 속성
          <a> href=""</a>태그 안쪽에 링크를 건다
          <a> href="" target="_blank"</a> 하면 새탭으로 링크를 연다

          클라이언트 태그의 중첩과 목록
          <li>태그
          <ul>태그(그룹)
          <ol>태그 (숫자)

          문서의 구조
          <tittle>(탭의제목)
          <meta charset="utf-8" (쀅훽룩 이렇게 나오는거 한국말로 나옴)
          <head>,<body>


          DOCTYPE
          <!doctype html> 은 브라우저에게 이 문서는 어떤 형식의 태그들이야, 라고 알려준다.





-01/06     
             웹사이트 만들기

             모르는것은 구글에 검색 ex) html button tag 검색



             개발도구

             meta 태그는 닫지 않는다


             단락-p 태그

             단락을 나눌때 사용함, 단락의 여백의 크기는 css를 통해 설정가능


             줄바꿈 -br

             줄바꿈 태그
             br은 닫지 않아도 된다
             p태그는 닫아줘야 한다.


             이미지 - img
             <img src=".jpg">


             표1 -table


            <table border="2"> <-표에 선 생기기 위한 태그

             <tr> <-구분짓기 위한 태그
                  <td>이름</td>     <td>성별</td>   <td>주소</td> <- 칸나누기
             </tr>
             <tr>
                  <td>최진혁</td>  <td>남</td>      <td >청주</td>
             </tr>
              <tr>
                  <td>최유빈</td>  <td>여</td>      <td>청주</td>
             </tr>



-01/07       



             표2-table

             <thead></thead>, <tbody></tbody> 내용의 정보와 제목 알려주기

             <td>태그를 <th>로 바꾸면 글씨가 진하게 나옴

             <tfoot>태그는 제일 밑의 데이터를 나타내줌




             표3-table

             <td rowspan="2"> 청주라고 하면 행이 병합됨 그래서 병합되는 부분에
             <td>는 지워줘야 한다 여기서 숫자 2는 행 2개를 병합한다는 뜻
             <td colspan="2"> 는 열을 합칠때하는 것이다.



-01/09       

            입력양식-form
            <html>
            <body>
            <form action="httt://localhost/login.php"> 이 주소로 로그인 정보 넘어감
            <p>아이디:<input type="text" name="id"></p> 아이디를 문자로 칠수있는 박스생김
            <p>비밀번호<input type="password" name="password"></p> 비밀번호를 치면****나옴
            주소:<input type="text" name="address"> 제출 버튼 만들어 줌
            </form>
            </body>
            </html>




            텍스트 입력

            text area는 여러줄 입력할때 사용
            text area내에서 cols 혹은 rows등의 속성을 이용하여 크기 행 정할수있음
            <p>text area: <textarea cols="50" rows="3"> default value</textarea> </p>
                                                             (여기)
            text area의 경우 열리고 닫히는 태그안에 써준다.  
            input은 닫아주는 태그가 없고 text area는 닫힌태그가 존재하며 열린태그와 닫힌태그안에 기본값을 넣어준다.






-01/10      



            선택

            붉은색~검은색을 option태그 걸어서 각각 선택가능하도록 그리고 콤보박스를 만들기 위해 select로 묶어주기
            그리고 데이터를 전송하기 위해 submit버튼을 만들어주고 데이터를 전송할때는 이름이 반드시 필요하기 때문에 select태그에 이름을 만들어줌.
            우리눈에는 검은색 파란색이 보이지만 컴퓨터가 정보를 인식하도록 option에 value속성을 줌

            <input type="radio" 버튼이 한개 생김 이름을 동일시하게 주면 한개만 선택가능
            붉은색: <input type="radio" name="color">
            검은색: <input type="radio" name="color">
            파란색: <input type="radio" name="color">
            - 컴퓨터에 정보를 주기위해 value 속성을 사용
            붉은색: <input type="radio" name="color" value="red">
            검은색: <input type="radio" name="color" value="black">
            파란색: <input type="radio" name="color" value="blue">
            -다중버튼을 사용하기위해서는 checkbox를 사용
            -checked 속성을 넣으면 기본적으로 선택되어 있게 할 수 있음.





            버튼

            - <input type="submit" value="전송"> value값을 주지 않으면 제출버튼이 생기지만 value="00"값을 주면 00버튼이 생김
            -<input type="button" value="버튼"> value값을 주지 않으면 빈칸의 버튼이 생기가 value값으로 이름을 줄 수 있음 but이경우에는 버튼을 눌러도 아무것도 발생되지 않음
            <input type="button" value="버튼" onclick="alert('hello world')"> 이런식으로 자바스크립트를 이용하여 사용해야함
            -<input type="reset"> form태그 안에 있는 모든 정보가 리셋됨.




            데이터 전송 -hidden

            hidden의 경우 url가 눈에 보이지는 않지만 데이터가 전송됨.
            url가 필요없거나 혹은 사용자 몰래 어떤 값을 서버로 전송할 필요가 있을 때 쓰임.
