# LMK-BOOK
(tutoring 2024-1 / 김수아 튜티) 사용자의 도서 목록을 분석하여 책을 추천해주는 추천 서비스

---

5/5 ~ 6/8

html 및 css 구현 후 js 파일을 사용하여 교보문고 페이지를 불러옴

---

+ LMK BOOK

>LMKBOOK.html
>
>검색.html
>
>책 정보.html
>
>style.css
>
>style2.css
>
>style3.css
>
>script.js

---

#### 검색 페이지
<!DOCTYPE html>
<head>
    <title>책 검색</title>
</head>
<body>
    <div>
        <h1>책 검색</h1>
        <input type="text" id="title" name="title" placeholder="내용 입력">
        <button class="btn" onclick="location.href='책 정보.html'">검색</button>
    </div>
</body>
</html>

#### 책 정보 페이지
<!DOCTYPE html>
<head>
    <title>책 정보</title>
</head>
<body>
    <h1>LMK BOOK</h1>
    <button id="btn1">책 보러가기</button>
    <button id="btn2">비슷한 장르의 추천 책 보러가기</button>
</body>
</html>

---

###작동방식
메인 페이지에서 책 검색 버튼을 누르면 검색 페이지로 연결됨

검색 페이지에서 내용 입력 후 검색 버튼을 누르면 원하는 책 정보를 선택할 수 있는 페이지로 연결됨

검색한 책 정보 또는 비슷한 장르의 책 정보 버튼을 클릭하면 교보문고 사이트로 연결됨

