# my-first-web-site<!doctype html>
<html>
<head>
<title> WEB1- HTML </title>
<meta charset="utf-8">
</head>
<body>
  <h1><a href = "index.html" target="_blank">WEB</a></h1>
<ol>
<li> <a href = "1.html" target="_blank">HTML</a></li>
<li> <a href = "2.html" target="_blank">CSS</a></li>
<li> <a href = "3.html" target="_blank">JavaScript</a></li>
</ol>
<h2><a href="https://www.w3.org/TR/2011/WD-html5-20110405/" target="_blank" title="html5 specification">HTML이란 무엇인가?</a></h2>
<p><iframe width="560" height="315" src="https://www.youtube.com/embed/7T7r_oSp0SE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>

<h4>웹페이지 만드는 코드 :HTML이라는 언어이다.</h4>
<strong>웹페이지 확장자 <u>HTML</u></strong>
<p>위에  strong태그는 글자를 진하게 해주는 태그이다.
        u 태그는 글자에 밑줄을 쳐준다.</p>

h1 ~ h6 태그는 글씨크기 차이를 보여준다, 줄바꿈, 두께

<p>br태그 줄바꿈. p태그 단락인지 표현.
br 태그와 p태그의 차이점은 단락 구분 가능, 불가능이다.</p>
<br>css를 통해서 (style ="margin -top :45px;") 단락 여백을 조절가능하다..
<br>html로 코딩한 검색엔진이 더 위쪽으로 올라옴.

<p>img태그 (source="이미지 이름" width =100%)
source는 이미지 부과, width는 사진의 배율</p>

<p>*목차
li태그는 목차를 만드는태그이다. ul태그는 li태그의 부모태그이다.
ol태그는 넘버를 붙혀주는 태그이다.</p>

<br>ctrl키 누른상태에서 커서를 클릭하면 한꺼번에 클릭가능
<p>*구조
meta태그는 저장된 방식을 바꿔주는 역할을 한다.<br>

title,meta 태그는 본문이 무엇인지 설명해준다.<br>

본문은 body태그로 묶는 것이다.<br>

body태그를 설명하는 태그는 head태그이다.<br>

이 모든것을 묶는 태그는 html 태그이다.</p>

<p>a태그는 링크를 걸 수 있다.
<br>(a href="링크" target="_blank" title="html5 specification")
href는 링크를 탈 수 있도록 도와주며 target은 새창을 열어라 라는 의미이다.</p>
<br>iframe 태그는 동영상 삽입을 가능하게 한다.</br>
<img src="coding.jpg" width="25%">
<br><div id="disqus_thread"></div>
<script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
    /*
    var disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://my-first-web-site-4.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript></br>
</body>
</html>
