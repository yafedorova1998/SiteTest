# SiteTest
<html>
<head>
<title>Мифы Древней Греции и Древнего Рима</title>
<style> 
q {
font-family: Times, serif; 
font-style: italic; 
font-size:19;
color: #002137;}
span {
color:#000000;
font-size: 25;
font-face: sans-serif;}
cite {
font-family: Times, serif; 
color: #002137;
font-size: 19;
font-face: sans-serif;}
a { 
text-decoration: none; /* Отменяем подчеркивание у ссылки */
margin: 0 20px;
color: #000000;} 
ul{
font-family: Times, serif; 
font-size:20;
color: #000000;
text-align: center;
list-style-type: none;}
#gor {
    margin:10;
    list-style-type: none;
    }
#gor li { display: inline; }
p{
font-size:20;
font-weight: 700;
text-indent: 20px;}

[class^="scroll"] {
position: relative;
height: 10em;
line-height: 10em;
padding: 10 3em;
}
[class^="scroll"] input {
display: none;
}
[class^="scroll"] div {
height: 300%;
overflow: hidden;
white-space: nowrap;
word-wrap: normal;
font-size: 0;
margin-bottom: 25px;
}
[class^="scroll"] img {
position: relative;
right: 0em;
width: 35%;
height: 100%;
transition: .5s;
margin: 20px;
}
[class^="scroll"] label {
cursor: pointer;
position: center;
font-weight: 200;
font-size: 3em;
}
[class^="scroll"] input:nth-of-type(1):checked ~ label:nth-of-type(2):after,
[class^="scroll"] input:nth-of-type(2):checked ~ label:nth-of-type(3):after,
[class^="scroll"] input:nth-of-type(3):checked ~ label:nth-of-type(4):after,
[class^="scroll"] input:nth-of-type(4):checked ~ label:nth-of-type(5):after,
[class^="scroll"] input:nth-of-type(5):checked ~ label:nth-of-type(6):after,
[class^="scroll"] input:nth-of-type(6):checked ~ label:nth-of-type(7):after,
[class^="scroll"] input:nth-of-type(7):checked ~ label:nth-of-type(8):after,
[class^="scroll"] input:nth-of-type(8):checked ~ label:nth-of-type(9):after,
[class^="scroll"] input:nth-of-type(9):checked ~ label:nth-of-type(10):after,
[class^="scroll"] input:nth-of-type(10):checked ~ label:nth-of-type(11):after,
[class^="scroll"] input:nth-of-type(11):checked ~ label:nth-of-type(12):after,
[class^="scroll"] input:nth-of-type(12):checked ~ label:nth-of-type(13):after,
[class^="scroll"] input:nth-of-type(13):checked ~ label:nth-of-type(14):after,
[class^="scroll"] input:nth-of-type(14):checked ~ label:nth-of-type(15):after,
[class^="scroll"] input:nth-of-type(15):checked ~ label:nth-of-type(16):after,
[class^="scroll"] input:nth-of-type(16):checked ~ label:nth-of-type(17):after,
[class^="scroll"] input:nth-of-type(17):checked ~ label:nth-of-type(18):after,
[class^="scroll"] input:nth-of-type(18):checked ~ label:nth-of-type(19):after,
[class^="scroll"] input:nth-of-type(19):checked ~ label:nth-of-type(20):after{
content: "\3009";
position: absolute;
right: 0;
}
[class^="scroll"] input:nth-of-type(2):checked ~ label:nth-of-type(1):after,
[class^="scroll"] input:nth-of-type(3):checked ~ label:nth-of-type(2):after,
[class^="scroll"] input:nth-of-type(4):checked ~ label:nth-of-type(3):after,
[class^="scroll"] input:nth-of-type(5):checked ~ label:nth-of-type(4):after,
[class^="scroll"] input:nth-of-type(6):checked ~ label:nth-of-type(5):after,
[class^="scroll"] input:nth-of-type(7):checked ~ label:nth-of-type(6):after,
[class^="scroll"] input:nth-of-type(8):checked ~ label:nth-of-type(7):after,
[class^="scroll"] input:nth-of-type(9):checked ~ label:nth-of-type(8):after,
[class^="scroll"] input:nth-of-type(10):checked ~ label:nth-of-type(9):after,
[class^="scroll"] input:nth-of-type(11):checked ~ label:nth-of-type(10):after,
[class^="scroll"] input:nth-of-type(12):checked ~ label:nth-of-type(11):after,
[class^="scroll"] input:nth-of-type(13):checked ~ label:nth-of-type(12):after,
[class^="scroll"] input:nth-of-type(14):checked ~ label:nth-of-type(13):after,
[class^="scroll"] input:nth-of-type(15):checked ~ label:nth-of-type(14):after,
[class^="scroll"] input:nth-of-type(16):checked ~ label:nth-of-type(15):after,
[class^="scroll"] input:nth-of-type(17):checked ~ label:nth-of-type(16):after,
[class^="scroll"] input:nth-of-type(18):checked ~ label:nth-of-type(17):after,
[class^="scroll"] input:nth-of-type(19):checked ~ label:nth-of-type(18):after, 
[class^="scroll"] input:nth-of-type(20):checked ~ label:nth-of-type(19):after{
content: "\3008";
position: absolute;
left: 0;
}

[class^="scroll"] input:nth-of-type(2):checked ~ div img {right: 25%;}
[class^="scroll"] input:nth-of-type(3):checked ~ div img {right: 50%;}
[class^="scroll"] input:nth-of-type(4):checked ~ div img {right: 75%;}
[class^="scroll"] input:nth-of-type(5):checked ~ div img {right: 100%;}
[class^="scroll"] input:nth-of-type(6):checked ~ div img {right: 125%;}
[class^="scroll"] input:nth-of-type(7):checked ~ div img {right: 150%;}
[class^="scroll"] input:nth-of-type(8):checked ~ div img {right: 175%;}
[class^="scroll"] input:nth-of-type(9):checked ~ div img {right: 200%;}
[class^="scroll"] input:nth-of-type(10):checked ~ div img {right: 225%;}
[class^="scroll"] input:nth-of-type(11):checked ~ div img {right: 250%;}
[class^="scroll"] input:nth-of-type(12):checked ~ div img {right: 275%;}
[class^="scroll"] input:nth-of-type(13):checked ~ div img {right: 300%;}
[class^="scroll"] input:nth-of-type(14):checked ~ div img {right: 325%;}
[class^="scroll"] input:nth-of-type(15):checked ~ div img {right: 350%;}
[class^="scroll"] input:nth-of-type(16):checked ~ div img {right: 375%;}
[class^="scroll"] input:nth-of-type(17):checked ~ div img {right: 400%;}
[class^="scroll"] input:nth-of-type(18):checked ~ div img {right: 425%;}
[class^="scroll"] input:nth-of-type(19):checked ~ div img {right: 450%;}
[class^="scroll"] input:nth-of-type(20):checked ~ div img {right: 475%;}
	</style>
</head>
 <body background= image/1.jpg>
 <img src="image/QR.gif" align="right" width="60px" height="60px"/>
 <a href="https://yandex.ru"><p><img src="image/yandex.png" align="right" width="50px" height="50px"/></p></a>
 <a href="https://www.google.ru"><p><img src="image/google.png" align="right" width="50px" height="50px"/></p></a>
<font face = sans-serif </font>
<h1 align=center > <i>Мифы Древней Греции и Древнего Рима</i></h1>
 <hr size=2 width=60% color=#ffffff>
 <ul id="gor">
<li><a href="mifgr.html">МИФЫ ДРЕВНЕЙ ГРЕЦИИ</a></li>
<li><a href="mifrm.html">МИФЫ ДРЕВНЕГО РИМА</a></li>
<li><a href="mifkl.html">МИФЫ В КИНО И ЛИТЕРАТУРЕ</a></li>
<li><a href="mifrz.html">ОСНОВНЫЕ РАЗЛИЧИЯ В МИФАХ</a></li>
</ul>
 <marquee behavior="alternate" onmouseout="this.start()" onmouseover="this.stop()"> <span><b><i>Вы готовы окунуться в фантастический мир мифов? </i></b> </span></marquee>
 <q>Зевс, взял себе небо, <br> Посейдон – море, <br> а Аид – подземное царство душ умерших</q>
 <br><cite>"Легенды и мифы Древней Греции" Николай Кун </cite>
 <p> <font size="30" color="red" face="Comic Sans MS">М</font>иф (др.-греч. μῦθος) — сказание, передающее представления людей о мире, 
 месте человека в нём, о происхождении всего сущего, о богах и героях.</p>
 <p>Согласно некоторым источникам, Древний Рим на протяжении столетий не имел собственной мифологии. 
 В то же время в соседней Греции культурная и религиозная жизнь людей процветала. 
 Многие современные исследователи, увлекающиеся историей Римской империи, склонны считать, что большинство мифов было позаимствовано ею ранее 
 у более развитых в культурном смысле греков, а римские боги – это боги, наделенные теми же силами и чертами, что и греческие. 
 Единственное их отличие заключается в именах. Так, богиня любви в римской мифологии - Венера - является точной копией греческой Афродиты. 
 Покровитель древнеримских искусств - Феб - как никто иной походит на греческого Аполлона и т.д. </p>

<div class="scroll">

<input type="radio" id="l" name="raz" checked="checked"/>
<input type="radio" id="2" name="raz"/>
<input type="radio" id="3" name="raz"/>
<input type="radio" id="4" name="raz"/>
<input type="radio" id="5" name="raz"/>
<input type="radio" id="6" name="raz"/>
<input type="radio" id="7" name="raz"/>
<input type="radio" id="8" name="raz"/>
<input type="radio" id="9" name="raz"/>
<input type="radio" id="10" name="raz"/>
<input type="radio" id="11" name="raz"/>
<input type="radio" id="12" name="raz"/>
<input type="radio" id="13" name="raz"/>
<input type="radio" id="14" name="raz"/>
<input type="radio" id="15" name="raz"/>
<input type="radio" id="16" name="raz"/>
<input type="radio" id="17" name="raz"/>
<input type="radio" id="18" name="raz"/>
<input type="radio" id="19" name="raz"/>
<input type="radio" id="20" name="raz"/>

<label for="l"></label>
<label for="2"></label>
<label for="3"></label>
<label for="4"></label>
<label for="5"></label>
<label for="6"></label>
<label for="7"></label>
<label for="8"></label>
<label for="9"></label>
<label for="10"></label>
<label for="11"></label>
<label for="12"></label>
<label for="13"></label>
<label for="14"></label>
<label for="15"></label>
<label for="16"></label>
<label for="17"></label>
<label for="18"></label>
<label for="19"></label>
<label for="20"></label>
<div>
<img src="image/1p.jpg" width="700px" title="Олимпийцы"/>
<img src="image/2p.jpg" width="700px" title="Зевс/Юпитер"/>
<img src="image/3p.jpg" width="700px" title="Посейдон/Нептун"/>
<img src="image/4p.jpg" width="700px" title="Аид/Плутон"/>
<img src="image/5p.jpg" width="700px" title="Гера/Юнона"/>
<img src="image/6p.jpg" width="700px" title="Деметра/Церера"/>
<img src="image/7p.jpg" width="700px" title="Гестия/Веста"/>
<img src="image/8p.jpg" width="700px" title="Афина/Минерва"/>
<img src="image/9p.jpg" width="700px" title="Арес/Марс"/>
<img src="image/10p.jpg" width="700px" title="Афродита/Венера"/>
<img src="image/11p.jpg" width="700px" title="Гефест/Вулкан"/>
<img src="image/12p.jpg" width="700px" title="Гермес/Меркурий"/>
<img src="image/13p.jpg" width="700px" title="Аполлон/Феб"/>
<img src="image/14p.jpg" width="700px" title="Артемида/Диана"/>
<img src="image/15p.jpg" width="700px" title="Дионис/Либер"/>

</div>
</div>

</body>
</html>
