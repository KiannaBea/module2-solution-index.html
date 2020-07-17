<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Assignment Solution for Module 2</title>
<link rel="stylesheet" type="text/css" href="Assignment Solution for Module 2 CSS.css">
<style>
	
* {
	font-family: monospace;
	box-sizing: border-box;
	margin: 0;
	padding: 0;
}
h1 {
	text-align: center;
	padding: 25px;
}
p {
	color: black;
	font-size: 14px;
}
.boxing {
	padding: 5px;
}
#Chicken {
	font-size: 15px;
	background-color: Gray;
	border: 1px solid black;
	height: 180px;
	width: 350px;
	float: left;
	position: relative;
	margin: 5px;
	padding: 10px;
	padding-top: 0px;
}
#Beef {
	font-size: 15px;
	background-color: Gray;
	border: 1px solid black;
	height: 180px;
	width: 350px;
	float: left;
	position: relative;
	margin: 5px;
	padding: 10px;
	padding-top: 0px;
}
#Sushi {
	font-size: 15px;
	background-color: Gray;
	border: 1px solid black;
	height: 180px;
	width: 350px;
	float: left;
	position: relative;
	margin: 5px;
	padding: 10px;
	padding-top: 0px;
}
.submenu {
	float: right;
	border: 1px solid black;
	width: 100px;
	padding: 5px 12px 5px 12px;
	position: relative;
	text-align: center;
}
.content {
	text-align: left;
	padding: 5px;
	clear: both;
}
#bigbox {
	position: relative;
	width: 100%;
}
#Chicken-cont {
	background-color: #21DEB5;
}
#Beef-cont {
	background-color: #5621DE;
}
#Sushi-cont {
	background-color: #DE214A;
}

/********** Large devices only **********/
@media (min-width: 992px) {
	.boxing {
		width: 33.33%;
		float: left;
	}
}

/********** Medium devices only **********/
@media (min-width: 768px) and (max-width: 991px) {
	.boxing1,
	.boxing2 {
		width: 50%;
		float: left;
	}
	.boxing3 {
		width: 100%;
		float: left;
	}
}

/********** Small devices only **********/
@media (max-width: 767px) {
	.boxing {
		width: 100%;
		float: left;
	}
}

</style>
</head>
<body>
<h1>Our Menu</h1>
<div id="bigbox">
	<div class="boxing boxing1">
		<div id="Chicken">
			<p class="submenu" id="Chicken-cont">Chicken</p>
			<p class="content">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
		</div>
	</div>
	<div class="boxing boxing2">
		<div id="Beef">
			<p class="submenu" id="Beef-cont">Beef</p>
			<p class="content">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
		</div>
	</div>
	<div class="boxing boxing3">
		<div id="Sushi">
			<p class="submenu" id="Sushi-cont">Sushi</p>
			<p class="content">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
		</div>
	</div>
</div>
</body>
</html>
