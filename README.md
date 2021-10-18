# presentation.acay
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
        <meta http-equiv= x-ua-compatible content= ie=edge>
        <meta name="viewport" content="width=device-width", initial-scale="1.0">
	<link rel="stylesheet" type="text/css" href="Home.css">
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link href="https://fonts.googleapis.com/css2?family=WindSong&display=swap" rel="stylesheet">
	<link href="https://fonts.googleapis.com/css2?family=Baloo+Chettan+2&display=swap" rel="stylesheet">
	<link rel="icon" href="https://www.oreca.com/wp-content/uploads/2017/04/acay-logo.png" type="image/icon type">
	<title>ACAY Mission Philippines Inc.,</title>
	<style>
		*
{
	margin: 0;
	padding: 0;

}
.banner{
	width: 100%;
	height: 100vh;
	background: url(jj.jpg);
	background-size: cover;
	background-position: center;
}

.navbar{
	width: 85%;
	margin: auto;
	padding: 35px 0;
	display: flex;
	align-items: center;
	justify-content: space-between;
}

.logo{
	width: 100px;
	cursor: pointer;
}

.navbar ul li{
	list-style: none;
	display: inline-block;
	margin: 0 20px;
	position: relative;
}

.navbar ul li a{
	text-decoration: none;
	color: rgb(0, 0, 0);
	text-transform: uppercase;
}

.navbar ul li::after{
	content: '';
	height: 3px;
	width: 0;
	background: black;
	position: absolute;
	left: 0;
	bottom: -10px;
	transition: 0.5s;
}

.navbar ul li:hover::after{
	width: 100%;
}

.content{
	width: 100%;
	position: absolute;
	top: 50%;
	transform: translateY(-50%);
	text-align: center;
	color: rgb(0, 0, 0);

}

.content h1{
	font-size: 100px;
	margin-top: 60px;
	font-family: 'WindSong', cursive;
}

.content p{
	font-size: 25px;
	margin: 30px auto;
	font-weight: 100;
	line-height: 25px;
	font-family: 'Baloo Chettan 2', cursive;
}


	</style>

</head>
<body>
	<div class="banner">
		<div class="navbar">
			<img src="acay-logo.png" class="logo">
			<ul>
				<li><a href="Home.html">Home</a></li>
				<li><a href="vmg.html">VMG</a></li>
				<li><a href="pedagogical.html">Pedagogical Approach</a></li>
				<li><a href="educere.html">Educere and Core Values</a></li>
				<li><a href="About.html">About</a></li>
			</ul>
		</div>

		<div class="content">
			<h1>Welcome!</h1>
			<p><strong>Good day to each and everyone!</strong> Welcome to my website presentation!</p>

		</div>
		
</body>
</html>
