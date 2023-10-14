<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>산업대학교</title>
    <style>
        /* reset */
        * {margin: 0; padding: 0;}
        .clearfix::before, .clearfix::after {display: block; content: ''; clear: both;}

        /* 레이아웃 */
        #wrap {width: 1200px; margin: 0 auto;}

        /* header */
        #header {}
        #header .logo {float: left; width: 250px; height: 100px; background: #888;}
        #header .nav {float: left; width: 950px; height: 100px; background: #777;}

        /* banner */
        #banner {height: 300px; background: #666;}

        /* contents */
        #contents {}
        #contents > div {float: left; width: 400px; height: 200px;}
        #contents > div.cont1 {background: #555;}
        #contents > div.cont2 {background: #444;}
        #contents > div.cont3 {background: #333;}

        /* footer */
        #footer {}
        #footer .foot1 {float: left; width: 200px; height: 100px; background: #888;}
        #footer .foot2 {float: left; width: 800px; height: 100px; background: #777;}
        #footer .foot3 {float: left; width: 200px; height: 100px; background: #666;}
    </style>
</head>
<body>
    <div id="wrap">
        <header id="header" class="clearfix">
            <h1 class="logo">로고</h1>
            <div class="nav">메뉴</div>
        </header>
        <!-- //header -->
        
        <section id="banner">
            <h2>이미지 슬라이드</h2>
        </section>
        <!-- //banner -->
        
        <section id="contents" class="clearfix">
            <div class="cont1"><h3>공지사항</h3></div>
            <div class="cont2"><h3>갤러리</h3></div>
            <div class="cont3"><h3>팝업</h3></div>
        </section>
        <!-- //contents -->
            
        <footer id="footer" class="clearfix">
            <div class="foot1"><h3>로고</h3></div>
            <div class="foot2"><h3>Copyright</h3></div>
            <div class="foot3"><h3>SNS</h3></div>
        </footer>
        <!-- //footer -->
    </div>
    <!-- //wrap -->
</body>
</html>
