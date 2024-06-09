# web-sayfas-
Div içinde Html Css kullanılarak web sayfası<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>örgü dünyası</title>
<link href="style.css" rel="stylesheet" type="text/css" />
<script type="text/javascript">
<!--
function MM_openBrWindow(theURL,winName,features) { //v2.0
  window.open(theURL,winName,features);
}
//-->
</script>
	<style> 
		@charset "utf-8";
body {
	background-image: url(arkaplan.jpg);
	background-repeat: repeat;
}
#header {
	background-image: url(HEADER.png);
	height: 120px;
	width: 1000px;
	padding: 10px;
	margin-right: auto;
	margin-left: auto;
	border: 1px solid #000000;
	border-radius: 25px;
}
#yataymenü {
	background-color: #FFFFFF;
	height: 60px;
	width: 1010px;
	margin-top: 20px;
	border: 1px solid #000000;
	margin-right: auto;
	margin-left: auto;
	border-radius: 25px;
}
#conteiner {
	height: 450px;
	width: 1000px;
	margin-top: 20px;
	border: 2px solid #000000;
	margin-right: auto;
	margin-left: auto;
	background-color: #FFFFFF;
	border-radius: 20px;
}
#dikeymenü {
	height: 400px;
	width: 300px;
	background-color: #E0C9C1;
	border: 1px solid #000000;
	float: left;
	margin-top: 20px;
	margin-left: 5px;
	border-radius: 20px;
}
#içerik {
	background-color: #E0CCC5;
	height: 400px;
	width: 650px;
	float: right;
	margin-top: 20px;
	margin-right: 10px;
	padding-left: 10px;
	border: 1px solid #000000;
	border-radius: 25px;
	
	 
}

#conteiner #dikeymenü ul {
	margin: 0px;
	padding: 0px;
	list-style-type: none;
}
#footer {
	background-color: #FFFFFF;
	height: 100px;
	width: 1000px;
	margin-top: 20px;
	margin-right: auto;
	margin-left: auto;
	border: 1px solid #000000;
	background-image: url(logo.png);
	background-repeat: no-repeat;
	border-radius: 25px;
}
#footer a {
	text-decoration: none;
	font-weight: bold;
	color: #000000;
}

#conteiner #dikeymenü a {
	display: block;
	height: 70px;
	width: 250px;
	margin: 5px;
	background-color: #000000;
	font-weight: bolder;
	color: #FFFFFF;
	text-decoration: none;
	line-height: 60px;
	font-style: italic;
	padding-left: 10px;
	border-radius: 25px;
}

#yataymenü ul {
	margin: 0px;
	padding: 0px;
	list-style-type: none;
	
}
#yataymenü li {
	float: left;
	position: relative;
	background-color: #000000;
	height: 40px;
	width: 180px;
	margin: 10px;
	padding: 1px;
	border-radius: 25px;
}
#yataymenü a {
	display: block;
	height: 40px;
	font-weight: bold;
	color: #FFFFFF;
	text-decoration: none;
	padding-left: 10px;
	line-height: 40px;
}
#yataymenü a:hover {
	display: block;
	height: 40px;
	font-weight: bold;
	color: #990000;
	text-decoration: none;
	padding-left: 10px;
	line-height: 40px;
}
#yataymenü ul li ul {
	display: none;
	position: absolute;
	left: 0px;
	top: 30px;
}
#yataymenü ul li:hover ul {
	display: block;
}
#conteiner #dikeymenü a:hover {
	display: block;
	height: 60px;
	width: 245px;
	margin: 5px;
	background-color: #990000;
	font-weight: bolder;
	color: #FFFFFF;
	text-decoration: none;
	line-height: 60px;
	font-style: italic;
	padding-left: 10px;
	border-radius: 25px;
}

 </style>
		
</head>

<body>
<div id="header"></div>
<div id="yataymenü">
  <ul>
    <li><a href="https://tr.wikipedia.org/wiki/%C3%96rme">ANA SAYFA</a></li>
	<li><a href="#">HAKKIMIZDA</a>
        <ul>
          <li><a href="#">Tarihçemiz</a></li>
        </ul>
    </li>
    <li onfocus="MM_openBrWindow('&quot;yem.jfif&quot;','içerik','width=300,height=300')"><a href="#">ÜRÜNLERİMİZ </a>
        <ul>
          <li><a href="yem.jfif">Tığ Oyalarımız </a></li>
          <li><a href="yelek.jfif">Tığ-Şiş Ürünlerimiz</a></li>
        </ul>
    </li>
    <li><a href="iletişim.html">İLETİŞİM</a></li>
  </ul>
</div>
<div id="conteiner">
  <div id="dikeymenü">
    <ul>
      <li><a href="battaniye2.jfif" onclick="MM_openBrWindow('battaniye1.jfif','','width=200,height=300');MM_openBrWindow('battaniye1.jfif','içerik','location=yes,width=300,height=300')">Battaniye Modelleri</a></li>
      <li><a href="yelek1.jfif">Yelek Modelleri</a></li>
      <li><a href="lif1.jfif">Lif Modelleri</a></li>
      <li><a href="pat1.jfif">Patik Modelleri</a></li>
      <li><a href="yem.jfif">Yemeni modelleri</a></li>
    </ul>
  </div>
  <div id="içerik">
    <p><a href="https://tr.pinterest.com/pin/305189312247348501/"><img src="yelek1.jfif" width="221" height="151" align="left" margin-left= "5px" /></a><img src="battaniye2.jfif" width="199" height="153" align="right" /><a href="https://www.elisihobiler.com/tigla-yapilan-petek-orgu-bayan-patik-yapimi/"><img src="pat1.jfif" alt="patik" width="225" height="153" align="middle" longdesc="pat1.jfif" /></a></p>
   
    <h1><a href="https://tr.pinterest.com/yenihobi/lif-modelleri/"><img src="lif1.jfif" alt="lif" width="236" height="150" align="left"  /></a><img src="yem.jfif" width="256" height="151" align="right" longdesc="yem.jfif" /><a href="https://hthayat.haberturk.com/orgu-yelek-modelleri-1072939"><img src="yelek.jfif" width="152" height="147" /></a></h1>
  </div>
</div>
<div id="footer">
  <div align="center"></div>
  <div align="center"></div>
  <div align="justify"></div>
  <div align="center">
    <blockquote>
      <p align="center">Örgü Dünyası örgü tariflerimizi örgüseverlerle paylaşmak</p>
      <blockquote>
        <p align="center">ve örgü sevenlerin görüp takip edebilecegi  bir platformdur.</p>
        <p align="right"><a href="#">İletişim İçin Buraya Tıklayınız</a></p>
    
  </div>
</div>

</body>
</html>

