# 💙visual studio code💙
=현재 필기하는 프로그램
## 사용방법 
- 이름.md 를 붙여야 # 같은 것들이 형성됨 <br>
-이름. html 붙여야 자동으로 </html> 등이 생김
-톱니바퀴-> Settings-> font size 16 <br>
-한줄로 나올 때 : 설정 -> wrap -> editor:on <br>
-보통 만들면 설명서 만들 때 있는데 그때 모든 설명서 이름 : README.md
-확장자 html, psd, ai, (gif, jpg, webm :웹소스)
-html : 브라우저가 인식하는 확장자, 4글자 확장자-> 최근 트렌드 4글자 확장자, htm 확장자 써도 상관 x
-크롬 (젤 많이 사용), 파이어폭스
-모든 컴에서 다 똑같이 나오지는 않아
readme 제작 명령어
markdown language : 사용설명서 만들기 

<>:태그, 태그로 이루어진 전체: 마크업
-태그는 속성과 부등호 명령어로 이루어 짐
body 의 부모는 html
html의 첫 자식 head 두번째 자식은 body
head와 body는 형제 관계
감싸있는 것인 부모 자식 관계

- html, css는 형들,부모는 못건들고 동생, 자식만 건들수 있으/자바는 다 건들수 있어 

비쥬얼 스튜디오에서 live server 깔아 
: 진짜 서버 만든건 아니지만 서버인거 처럼 보여줘

  <img src="./image/sim.jpg" width="200" alt="설명">
 src="./images/sim.jpg" 이미지 속성
  width="200" 넓이 속성
  alt="" 설명 속성 <br>

## 기본 구조1
<html>  
 <head>
   <title> </title>
   <meta charset-"utf-8">
 </head>
 <body>
   1.
   2.
   3.
   <header>
   : <h1>
   </header>
   <section>
   <h2>
   </section>
   <footer>
   </footer>
 </body>
</html>

## 기본구조 설명
<html> :여기가 html 시작 / <>:태그, 태그로 이루어진 전체: 마크업
 <head 태그 안에는 환경 설정과 관련한 명령어 삽입> : 환경 설정
   <title> 브랜드 네임 </title>
   <meta charset-"utf-8">
 </head>
 <body>
   1. html : hyper text markup language <br>
   언어를 구분하는 단위 = 명령어 = 태그 = TAG <br>
   2.CSS: cascading style cheet <br>
   디자인을 입히는 언어 (꾸며주는 것) <br>
   3.javascript <br>
   :동적인 언어 (서로 다른 데이터(아이디) 넣어도 다 로그인 되는 것) <br>
   4.jQuery <br>
   = javascript로 만들어 둔 도구 = 프레임워크, 라이브러리 
   ( java를 쉽게 만든거)
   앵귤러, 뷰, 노드js
   -1,2 : 정적인 언어, 제한적 언어, 레고 조립형 언어, 1,2 두개로 완벽히 꾸밀 수 x
   -3,4 : 동적인 언어
   -&nbsp; : 띄어쓰기 한번 인식. 그 외에는 다 &nbsp; 로 
해야해 (ex. html &nbsp; &nbsp; &nbsp; -> 7번 띄움)
-<br> 문단 뛰기
 </body>
</html> :여기가 html 끝이다
 
## 기본구조 설명2 
-얘는 ! 탭으로 비쥬얼 스튜디오 코드 생성함
 <!DOCTYPE html>
<html lang="ko"> : 한글은 KO/kr ->이거 해두면 영어 사이트에서 선택 창 안나옴
    영어는 en   
<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>브랜드네임</title>
</head>
<body>
	<h1>로고이미지와 텍스트</h1> : 챕터 1,2,3 해더 첫번째. 여기에 넣었으면 하는 글 다 넣어야 함 (사이트에 안보이게 할 수 있어) -h1이 전체 페이지에서 무조건 하나는 있어야 해, 그림으로 들어가 있어도 글씨 있어야 검색됨, 그리고 시각 장애인들 위해 읽어줘야 하므로
	<h2>러블리슈즈 lovely shoes</h2> : 소제목 
	<h3>러블리슈즈 lovely shoes</h3> : 소소제목 
	<h4>러블리슈즈 lovely shoes</h4>
	<h5>러블리슈즈 lovely shoes</h5>
	<h6>러블리슈즈 lovely shoes</h6>
	<p> 본문에 사용될 텍스트 </p>
<!--페이지 내에 무조건 h1은 1개 이상 존재해야 함 (꼭 해더에 아니더라도)
    - h1 사용하다가 h4 등으로 뛰어넘기 해서 사용하지 말고 순차적으로 사용할것. h1에서 바로 h4로 넘어오면 안됨 (구글은 h1 후에 h2 후에 h3 찾음)
    -css로 수정하여 사용할 수 있음 (다른 크기 글씨 등 원할 때 )
    -키워드 검색 역할
    - h1~h6 까지만 사용 가능 - 글씨가 작아짐-->
    <script>
     console.log('vs code debug') ;
     // 로그: 상태확인(로그인이 아님). :이 안에 자바 스크립트 코드 들어감
     프로그램 실행 할 때 관찰되어야 하는 것 로그인 할때 아이디, 비번 입력하면 네이버에 데이
     터 잘 전달되는지 사람의 눈으로는 확인 할 수 없어 so 텍스트로 관찰되게 하는 것 
     </script>
   <header>
			<h1>로고이미지와 텍스트 (로고 글씨로 된 거 반드시 하나 있어야 함)</h1>
			<!-- header : 제목, 검색이 되기위한 메뉴 nav, 메인배너 -->
      <nav> 메뉴 중에서도 검색 대상이 되는 것들 </nav> 
       <nav> 검색이 되고 싶으면 nav에 감싸라, 색 따라 가면 뭐 된다 : nav,
      네비게이션: 건강 인->나의 건강관리 ->나의 위치에 대한 이런 안내,메뉴 </nav>
	 </header>
	 <section>
		  <h2>최소 1개이상 제목 필요</h2>
      <h2> 이하 반드시 section 에 넣어야 함</h2>
       <!---각종 콘텐츠, 배너, 카드형 레이아웃, 빠른찾기(퀵바),광고 등-->
       <div>:내용. 영역 확인, (포토샵으로 치면 레이어 하나)보통 내용 아무거나 다 여기다 넣어 
       </div>
    <arlticle> 
         :주제가 하나로 따로 빼도 되는 내용. 문단 (카테고리 하나)
         <figure>
             이미지 넣는 법 :
             -이미지 넣을 때 반드시 alt 넣어야 함. 시각 장애인을 위한 텍스트 리더기가 alt 안의 설명을 읽어줌. (웹접근성에 적합한 페이지 만들기 위해서는 넣어줘야 함)
             1. 더미 이미지를 넣을 수 있도록 도와주는 사이트
              (뒤에 크기도 설정)
             <img src="http://placekitten.com/400/300" alt="더미 이미지로 귀여운 고양이 사진">
             <img src="http://www.placehold.it/400x300" alt="">
             2. 원하는 이미지 주소 복사해서 넣기 
             (구글 등 들어가서 오른쪽 버튼 눌러 이미지 링크 복사)
             -<!-- 이미지 기본적인 가로너비는 픽셀 단위 기준으로 저장됨 
            hgight와 width는 비율에 맞춰 저장해야 하며 width만 조절하면 height는 자동으로 조절됨-->
             <img src="./images/sim.jpg" width="200" alt="심슨 가족이 거실에 모여있는 모습 메기가 가운데에 있고 뒤로 다른 심슨들이 있다">
             가로만 설정하면 자동으로 새로 형성함
             <img src="./images/sim.jpg" width="200" height="400">
             가로 세로 둘다 설정하면 비율이 안맞으면 찌글어짐
             3.내 컴에 저장된 이미지 
              <img src="images/tiger.jpg" width="100%">
              <img src="./벤치마킹1/minions">
             ./ :현재 폴더(생략 가능) ../ :상위 폴더
             <!--나(img)의 부모의 너비의 100%-->   
             지금 쓰는 태그 화면에 꽉차는 태그 ->100 퍼센트면 꽉차
             <!--% 단위는 생략할 수 없고 나(img)의 부모의 너비를 기준으로 % 비율로 사용.현재는 부모가 모든 브라우저 너비의 100% 상태임-->
         </figure>
     </arlticle>
    </section>
    <footer>
        <adress> 회사 주소, 연락처 </adress>
    </footer>
</body>
</html>

## 기본구조 설명3 ->sum1

<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>목록형 태그</h1>
    <h2>1. 순서가 있는 목록</h2>
    <ol>
    :오더드 리스트
    순서가 있는 목록 안에는 리스트가 있어야 해 (단순히 번호 순서가 아니라 진짜 순서)
        <li>웹 사이트 기획</li>
        <li>HTML5 마크업 언어(태그를 공부함)</li>
		<li>css3 디자인 언어</li>
		<li>javascript 객체지향적 언어</li>
		<li>jQuery 라이브러리</li>
    </ol>
    <ol type="A">
        <li>웹 사이트 기획</li>
        <li>HTML5 마크업 언어</li>
		<li>css3 디자인 언어</li>
		<li>javascript 객체지향적 언어</li>
		<li>jQuery 라이브러리</li>
    </ol>
    <ol type="a">
        <li>웹 사이트 기획</li>
        <li>HTML5 마크업 언어</li>
		<li>css3 디자인 언어</li>
		<li>javascript 객체지향적 언어</li>
		<li>jQuery 라이브러리</li>
    </ol>
    <ol type="I">
        <li>웹 사이트 기획</li>
        <li>HTML5 마크업 언어</li>
		<li>css3 디자인 언어</li>
		<li>javascript 객체지향적 언어</li>
		<li>jQuery 라이브러리</li>
    </ol>
    <ol type="i">
        <li>웹 사이트 기획</li>
        <li>HTML5 마크업 언어</li>
		<li>css3 디자인 언어</li>
		<li>javascript 객체지향적 언어</li>
		<li>jQuery 라이브러리</li>
    </ol>
    <ol start="10">
        <li>웹 사이트 기획</li>
        <li>HTML5 마크업 언어</li>
		<li>css3 디자인 언어</li>
		<li>javascript 객체지향적 언어</li>
		<li>jQuery 라이브러리</li>
    </ol>
    <ol type="A" start="10">
        <li>웹 사이트 기획</li>
        <li>HTML5 마크업 언어</li>
		<li>css3 디자인 언어</li>
		<li>javascript 객체지향적 언어</li>
		<li>jQuery 라이브러리</li>
    </ol>
    <ol>
        <li>웹사이트 기획</li>
        <ol>
            <li>요구조사</li>
            <li>아키텍쳐 디자인</li>
        </ol>
        <li>HTML5 마크업 언어</li>
		<li>css3 디자인 언어</li>
		<li>javascript 객체지향적 언어</li>
		<li>jQuery 라이브러리</li>
    <ol>
        <li>웹사이트 기획</li>
        <ul>
            <li>요구조사:의뢰인의 요구</li>
            <li>아키텍쳐 디자인(설계)</li>
        </ul>
        <li>HTML5 마크업 언어</li>
		<li>css3 디자인 언어</li>
		<li>javascript 객체지향적 언어</li>
		<li>jQuery 라이브러리</li>
    </ol>
    <h2> 2. 순서가 없는 목록</h2>
    <div>
       -순서가 없는 목록은 숫자 대신 블릿 기호로 나타냄 <br>
       -type = desc, circle, squre (지정안하면 디폴트 디스크) <br>
       -순서가 없는 목록 사용하는 때 : 메뉴 만들때 사용 (ex.메뉴 중 가방에 마우스 올리면 목록 나오는애들 (백, 클러치, 월릿...) <br>
       -ul>li*4 탭 : ul, 자식 li 4개 만들어라
       -스스로 자식은 다른 태그로 만듬
    </div>
    <ul>
        <li>딸기</li> :ul의 첫 번째 자식/li 끼리는 형제
        <li>복숭아</li>
        <li>망고</li>
        <li>감</li>
    </ul>
    <ul type="circle">
        <li>딸기</li>
        <li>복숭아</li>
        <li>망고</li>
        <li>감</li>
    </ul>
    </ul>
    <ul type="square">
        <li>딸기</li>
        <li>복숭아</li>
        <li>망고</li>
        <li>감</li>
    </ul>
    <ul>
        <li>좋아하는 과일 이름</li>
        <ul>
            <li>딸기</li>
            <li>복숭아</li>
            <li>망고</li>
            <li>감</li>
        </ul>
        <li>좋아하는 취미</li>
        <ul>
            <li>넷플릭스 앤 칠링</li>
            <li>친구들이랑 놀기</li>
            <li>자전거 타기</li>
            <li>보드 타기</li>
            <li>전시 관람</li>
        </ul>
        <li>좋아하는 음식</li>
        <ul>
            <li>한식</li>
            <ul>
               <li>미역국</li>
                <li>된장찌게</li>
            </ul>
            <li>중식</li>
            <ul>
                <li>꿔바로우</li>
                <li>깐초새우</li>
            </ul>
            <li>양식</li>
            <ul>
                <li>피자</li>
                <li>파스타</li>
            </ul>
        </ul>
        <li>좋아하는 영화</li>
        <ul>
            <li>스릴러</li>
            <ul>
                <li>지옥</li>
            </ul>
            <li>코미디</li>
            <ul>
                <li>모던패밀리</li>
            </ul>
            <li>애니메이션</li>
            <ul>
                <li>코렐라인</li>
            </ul>
        </ul>
    </ul>
    <h2>3.목록 타입을 표시하지 않기</h2>
    <div>
        - html 태그만으로는 모든 브라우저에 공통적으로 디자인 할 수 없고 (type="none 으로 하면 브라우저마다 달라 어떤 브라우저에서는 없어지고 어디선 안없어짐 ) 
		-크로스브라우징: css 스타일(style="list-style-type:none ;)을 이용한 디자인을 한다면 대부분 브라우저에 비슷한 디자인을 적용할 수 있다. (똑같은 디자인 아님) 
    </div>
    <ol type="none" style="list-style-type:none;">
        <li>웹사이트 기획</li>
        <ol type="none" style="list-style-type:none;">
            <li>요구조사</li>
            <li>아키텍쳐 디자인</li>
        </ol>
        <li>HTML5 마크업 언어</li>
		<li>css3 디자인 언어</li>
		<li>javascript 객체지향적 언어</li>
		<li>jQuery 라이브러리</li>
    </ol>
    <ul type="none" style="list-style-type:none;">
        <li>웹사이트 기획</li>
        <ul type="none" style="list-style-type:none;">
            <li>요구조사</li>
            <li>아키텍쳐 디자인</li>
        </ul>
        <li>HTML5 마크업 언어</li>
		<li>css3 디자인 언어</li>
		<li>javascript 객체지향적 언어</li>
		<li>jQuery 라이브러리</li>
    </ul>
    <h2> 4.정의형 목록타입</h2>
    <div>
        dl (데피니셜 리스트) <br>
       - > : 자식 , + : 형제 <br>
       - dl>dt+dd 탭 (dt딸, dd 아들 두 자식 있음) <br>
       - dt 용어, dd 뒤에 해설 같이 나옴
    </div>
    <dl>
        <dt>웹브라우저</dt>
        <dd>html, css, javascript 번역하는 도구</dd>
        <dt>웹브라우저 종류</dt>
        <dd>크롬, 사파리, 파이어폭스, 오페라,웨일즈,스윙...</dd>
    </dl>
</body>
</html>



# 제목: readme 제작 명령어
## 작은 제목
### 소제목(더 작은 제목) <br> <br>

# 기호, 부호 ## 외워야 할 공식

1. <img src="./벤치마킹1/minions">
<img src="./이미지가 들어있는 폴더명/이미지 이름"> <br>
->html에서 이미지 넣을 때 명령어
src (소스): 나랑 같은 경로에 있는 이라는 뜻 
2. <!--- : 주석-->
3. <br> :문단 띄기
4. &nbsp; : 한칸 띄기
5. <: &lt; >: &gt; ( 부등호는 명령어라 함부로 쓰면 안돼)
6. ! + 탭바 :visual code 생성 단축키
7. 왼화살 +옵션키 : 줄 복붙
8. <div style="background:skyblue;"> : 바탕색 칠하기 
<div,p,b 등 >
9.위 아래 키 누르면 이전 명령어 나와

# 단축키 등 컴퓨터
1. ! + 탭바 :visual code 생성 단축키
2. 왼화살 +옵션키 : 줄 복붙
3. <b>  shift 누른 상태에서 방향키 누르면 블럭 생성-> 컨트롤 x ->컨트롤 v </b>
4. home 키 누르면 커서 맨 앞, end 키 누르면 커서 맨 뒤로 
5. alt tab 창이동
6. 맥 한자 옵션 +엔터
7. command +s :저장
8.컨트롤 u 하면 그 사이트 코드 볼 수 있으
9.숨겨진 확장자 표시 




1.
  ``` 
 ` 백틱 : option+ ₩ / 그냥 ₩ 누르기 
 백틱 3번 연속 ``` 쓰면 이런 회색 창 형성 할 수 있음
 -설명, 영역 구분 등 할 때 

```
2. 숫자 계속 1. 로만 쳐도 자기가 알아서 다 바꿔줌
3. **진하게 표현** : ** 글씨 ** <br>
4.♥︎ ☃︎😀 이모지: command +control + space bar
5.lorem 치고 탭 (엔터) : 아무 영어 쭉 쳐짐
lorem *10 치고 탭(앤터)
그 외 더 많은 기능 <br>
마크다운 <br> 
https://www.markdownguide.org/
->cheat sheet :명령어 단축키 
https://velog.io/@wonhs717/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4Markdown-%EB%AC%B8%EB%B2%95-ytk5zemk0x#7-task-lists-%ED%95%A0%EC%9D%BC-%EB%A6%AC%EC%8A%A4%ED%8A%B8-%EC%B2%B4%ED%81%AC-%EB%A6%AC%EC%8A%A4%ED%8A%B8


# 명령 특징, 종류
1. 쌍으로 이루어진 명령 <html> </html> 
단일 명령 meta, img &nbsp; 
2.display 속성이 block 속성인 태그와 inline인 태그 
- block 속성 : 가로로 전체 채워짐 (글 있는 부분 이든 없는 부분 이든 가로 전체 채워짐) -넓으면 넓은대로 좁으면 좁은대로 글씨 화면에 꽉참 
<p>
-inline 속성의 태그: 일부 부분만 그렇게 됨 (글 있는 그 부분만 그렇게 됨)
1. <b> 진하게, bold </b> : 단순히 디자인 용도로 진하게
2. <strong>진하게 </strong> :검색이 되는 , 키워드가 될 단어
3. <i> 이탤릭체</i>
4. <em>키워드 검색되는 이탤릭체</em>
5. <u> 언더라인</u>
6. <ins>인서트라인</ins>
7. <mark>노란색 칠해줌</mark>
8. <sup> 수학기호 같이 위해 첨자,위 설명글</sup>
9. <sub>글씨가 아래로 </sub>



 -img는 공간이 되면 가로로 나열 (안되면 아래로 내려감) <br>
 -h1, p 아래 등은 br 안썼는데 줄 바뀜 <br>
    
   

# 기호이름
1. ` 백틱 : ₩ + option
1. ~ 틸드 
1. ^ 캐럿 
1. & 앰퍼센트 : 7번 
1. | 파이프 
1. \ 백슬래시 
1. / 슬래시 


# 파일명, 폴더명 사용시 주의점
html 소스로 사용할 이미지
1. 파일명은 반드시 영문으로 시작
1. 의미 있는 파일명 <BR>
 (EX.1월에 보이는 배너1)
1. 파일명, 폴더명은 반드시 띄어쓰기 사용하지 말 것
 - 서버: 리눅스 환경 (띄어쓰기 인식 X) (아무대서나 볼 수 있게 서버에 올려야 함 )
4. 대소문자 구분해서 사용할 것 (리눅스는 대문자와 소문자 다르게 인식. 대문자로 쓰면 소문자로 치면 못찾음)
+. 숫자 쓸때 01,001 이렇게 쓰기 (안그러면 순서가 뒤죽박죽 됨)

# 이름 만드는 규칙 : 문화, 학문 
1. 카멜표기법 : 단어와 단어 사이 첫 글자는 대문자 <br> 
:afterClass (c 대문자)
2. 스네이크 표기법: 단어와 단어 사이를 -로 표시 <BR> 
(뱀 처럼 길다 -----)
3. 파스칼 표기법: 첫글자를 대문자로 사용
4.

# 이미지 파일 확장자
## 웹에 업로드 할 수 있는 확장자
- jpg: 투명표현이 불가능
- png: 투명표현이 가능
- gif: 투명표현, 애니메이션 가능
- webm: 새로운 이미지 포맷 

# 명령체계 시스템

DOS :윈도우 환경 이전 
마우스로 컴퓨터 제어 = GUI (grapic user interface) :그래픽 환경 -> 그림으로 나와 마우스만 잘  : 윈도우, 맥, 레드햇
명령어로 제어= CUI(command user interface), CLI : 터미널, DOS, 리눅스, (그래픽 환경 니룩스, 명령어 써서 하는 리눅스 둘이 있음) 

서버환경: 리눅스 서버환경 (SO 명령어)
마이크로소프트사(윈도우) 서버 환경 드뭄

명령어 사용할 수 있는 편집 툴 : visual studio code (MS) + 라이브러리 = 프레임워크 = 플러그인 = 확장팩 (기업에서 추가한 것들)

                       :아톰, 서브라임, 드림위버 -> 브라킷(어도비): 지원포기
# 웹표준
: html5로 제작이 되어 있다. css3로 디자인했다. IE11(익스프로러11) 버전 이상만 인식 (IE5,6,7,8,9,10는 시맥틱 태그 인식 못함, div 만 인식함)
-웹표준에 적합하게 페이지 만들어야 함
-시멘틱 태그 : 용도가 정해진 태그 (header ,nav,section,footer,article,fi )

# 에디터:웹문서 편집기
vs code
아톰 
노트패드
sublime
메모장 (으로도 코딩 가능하다!)
드림위버
프론트페이지
나모웹에디터



# 컴파일러. 인터프리터
1.컴파일러
 프로그래밍: 영어로 명령어를 작성 (파일명.java,안드로이드.an 이런 파일 만들어짐)
 파일명.java ->01010100100000 1111 이런 기계어로 바꿈 (전기 흘렀다 안흘렀다로 기계가 알아들어) 이런 0101011110 111 파일명. 
 안드로이드.an -> 0000011000 안드로이드.apk (apk =플레이스토 받는 앱 확장자)
- 파일명.java는 인간이 써 이런 우리가 쓴거를-> 기계명으로 바꾸는 것을 컴파인 이라 함
- 컴파일러: 컴파일 하는애 (자바 컴파인 하는애, ios 컴파인 하는애 달라 )
- 버전 낮아서 안받아지는 거 컴파일러 형태임. 기계 종속적이됨 
 
2.인터프리터
:컴파일이 되지 않고 기계에 맞춰서 동작함 ( so 다른 브라우저에서 다 열려)
- 기계를 인식하고 인식된 기계에 맞춰서 번역함 (그때 그때 번역하는 )
- html, css, javascript

# 💙터미널,GIT💙
## 사용방법
컨트롤 누르고 마우스 키우면 글씨 커져 
# git: 리눅스 명령 환경
1.git-scm.com 다운로드
2.업로드 원하는 파일 있는 폴더로 들어가> 마우스 오른쪽 버튼 > git-bash here
3. 맥에서는 단축키 : 왼쪽 방향키

# git upload
<img src="./복습 첨부파일/git 올리기"> <br>
```
echo "# afterClass" >> README.md
//문서를 만든다. 
git init
// git 폴더 초기화
git add README.md
// git 업로드 할 파일 선택
(git add .) -> 다 올리는 것
(git status ->틀렸는지 아닌지 보는 것)
git commit -m "first commit"
// 버전 관리에 들어갈 설명 쓰기
commit :  수정될 때 마다 
git branch -M main
// master -> main 으로 이름이 바뀜 
git config --global user.email "suan0603@naver.com"
git config --global user.email "usuanyou"
//오픈소스니까 다른 사람이 내꺼보고 질문할 수 있도록
git remote add origin https://github.com/usuanyou/afterClass.git
//업로드할 폴더와 로컬폴더를 연결
-내 컴퓨터 안 폴더랑 git 폴더 연결
// staging: 업로드할 준비
git push -u origin main
// 진짜 업로드 함 -진짜 올리는 거
```

## git 업로드 주의 사항
-내가 git 과 연결한 정보 다 git 숨김 파일에 있음 -> 명령어 망하면 파일 지우고 다시 새로 시작하면 됨
-mac 숨긴 파일 보기 :command+ . + 오른쪽 화살표

# 두번째 접속 후 업로드
```
git remote add origin https://github.com/usuanyou/afterClass.git
git branch -M main
git push -u origin main
```

git init
git clone 사이트주소 
// 그 폴더 있는거 내 컴에 받는 것
아니면 그 사이트에서 다운로드 zip

# 기호 해석
.. 상위폴더, 아버지
. 현재 내 폴더에 있는 애들, 걔네가 내 형제들
- . 현재 폴더는 생략가능
../.. 상위상위
리눅스 시스템 $, %
독스 >

# CUI 사용하여 폴더관리 
**1. ls: 파일 목록 확인하기 / 도스 환경에서는 dir** <br>
yusuan-ui-MacBookPro:uiux youmac$ ls
README.md                                               암기.html                                               복습 첨부파일
SUMMERY.md                                              암기.md                                                 벤치마킹1
success                                                 과제1.docx
**2. pwd : 현재 위치 확인** <br>
yusuan-ui-MacBookPro:uiux youmac$ pwd
/Users/youmac/Desktop/uiux
**3. mkdir (make directory) 폴더명 : 현재 위치에 폴더 만들기** <br>
yusuan-ui-MacBookPro:uiux youmac$ mkdir folder
yusuan-ui-MacBookPro:uiux youmac$ ls
README.md                                               success                                                 과제1.docx
SUMMERY.md                                              암기.html                                               복습 첨부파일
folder                                                  암기.md                                                 벤치마킹1
**4. cd (change directory) 폴더명 : 그 폴더로 이동**  (현재 내가 있는 위치의 폴더만 가능한듯)
yusuan-ui-MacBookPro:uiux youmac$ cd success
yusuan-ui-MacBookPro:success youmac$ pwd
/Users/youmac/Desktop/uiux/success
**5. cd .. : 상위경로로 이동** 
yusuan-ui-MacBookPro:success youmac$ pwd
/Users/youmac/Desktop/uiux/success
yusuan-ui-MacBookPro:success youmac$ cd ..
yusuan-ui-MacBookPro:uiux youmac$ pwd
/Users/youmac/Desktop/uiux
yusuan-ui-MacBookPro:uiux youmac$ 
**6.git log :상태 확인** commit한 상태만 보여줌
**7. git config --list : 컨피그의 속을 보여달라** 
git 안에 저장된 환경정보 보여줌 
환경설정하려면. 이메일, 유저 이름 맞는지 확인
yusuan-ui-MacBookPro:uiux youmac$ git config --list
credential.helper=osxkeychain
user.name=usuanyou
user.email=suan0603@naver.com
**8.git config --unset --global user.name : 유저네임 초기화**
아무말 안나오면 정상적으로 된 것. 확인하려면 git config --list 
**9.git config --unset --global user.email :유저 이메일 초기화**
**10. git config --global user.name "usuanyou" :유저이름 usuanyou 로 재설정**
**11. rmdir : 빈 파일 삭제**
**sudo 앞에 붙이면 최고 명령자 이름으로 하는 것**

**6. rm : 하위폴더 지우기 
**7. rd : 폴더 전체 지우기
** git add . : 현재 폴더에 있는 모든 것
** *, ? " 모든 파일 
gitscm.com -> git 안되면 들어가 찾아봐 

ESC 키  w 빠져나와
**위 아래 키 누르면 이전 명령어 나와**
**command + + : 커져**


