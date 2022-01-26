# portfolio<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>
		Personal Portfolio Website
	</title>
	<link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
		<div class="hero">
			
<nav>
			<img src="4.jpg" class="me" height="200" width="300">
			<ul>
				<li title="Visit home?"><a href="#">HOME</a></li>
				<li title="Wanna know about me?"><a href="#">ABOUT	</a></li>
				<li title="wanna see my portfolio?"><a href="#">Portfolio</a></li>
				<li title="Here you'll see the list of services that I provide"><a href="#">SERVICES</a></li>
				<li title="If you're gonna hire me then you have a nice choice"><a href="#">HIRE ME</a></li>
			</ul>
		</nav>
		<div class="detel"> 
				<h1 title="About Sunil Giri">I'm Sunil <span>Giri</span></h1>
				<p>This is my official portfolio website to show all of my<br>Details and work experience of web development</p>
				<a href="#">DOWNLOAD CV</a>
		</div>
		
		</div>
			<div class="images">
			<img src="1972305.jpg" class="me">
		</div>
		<footer>
			<p><strong>
			Copyright &copy Jan 26, 2022 Sunil Giri
		</strong></p>
		</footer>

</body>
</html>body{
	margin-top: -16px;
	padding:0 ;
	font-family: sans-serif;
}
.hero{
	position: relative;
	width: 100%;
	height: 100vh;
	background: #eff4fd;

}
nav{
	display: flex;
	width: 84%;
	margin: auto;
	padding: 20px 0;
	align-items: center;
	justify-content: space-between;

}
nav ul li{
	display: inline-block;
	list-style: none;
	margin: 10px 20px 90px;
}
nav ul li a{
	text-decoration: none;
	color: #000;
	font-weight: bold;

}
nav ul li a:hover{
	 color: red;
}
.detel{
	margin-left: 18%;
	margin-top: 4%;
}
.detel h1{
	font-size: 50px;
	color: @212121;
	margin-bottom: 20px;
}
.detel a:hover{
     background-color: black;
     color: white;
}
span{
	color: orange;
 
}
.detel p{
	color: #555;
	line-height: 22px;
}
.detel a{
	background: #212121;
	padding: 10px 18px;
	text-decoration: none;
	font-weight:bold ;
	color: #fff;
	display: inline-block;
	margin: 30px 0;
	border-radius: 5px;

}
.images{
	width: 45%;
	height: 80%;
	position: absolute;
	bottom: 0;
	right: 100px;

}
.images img{
	height: 100%;
	position: absolute;
	left: 50%;
	bottom: 0;
	transform: translateX(-50%);
	transition: bottom 1s, left 1s;
}
.images img{
	height: 100%;
	position: absolute;
	left: 50%;
	bottom: 0;
	transform: translateX(-50%);
	transition: bottom 1s, left 1s;
}
footer{

	text-align: center;
	color: black;
}
}
