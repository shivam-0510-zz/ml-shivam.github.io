<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Gym</title>
</head>
<link rel="stylesheet" href="style.css">
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Epilogue:wght@500&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Epilogue:wght@500&family=Poppins:wght@500&display=swap"
	rel="stylesheet">

<body>
	<header class="header">
		<div class="left">
			<img src="https://upload.wikimedia.org/wikipedia/en/thumb/3/3f/Gold%27s_Gym_logo.svg/1200px-Gold%27s_Gym_logo.svg.png"
				alt="">
			<div class="gym">Gold's Gym</div>
		</div>
		<div class="mid">
			<ul class="navbar">
				<li><a href="#" class="active">Home</a></li>
				<li><a href="#">About Us</a></li>
				<li><a href="#">Fitness Center</a></li>
				<li><a href="#">Contact Us</a></li>
			</ul>
		</div>
		<div class="right">
			<button class="btn">Call Us Now</button>
			<button class="btn">Email Us</button>

		</div>
	</header>
	<hr class="h">
	<form action="backend.php" target="_blank">
		<input type="text" placeholder="Enter your name" class="frm"><br>
		<input type="text" placeholder="Enter your email-id" class="frm"><br>
		<input type="text" placeholder="Enter password" class="frm"><br>
		<input type="text" placeholder="Enter your phone number" class="frm"><br>
		<button class="btn">Submit</button>
	</form>
</body>

</html>
body{
    background: url(https://i.pinimg.com/originals/b8/8e/59/b88e5919775afd0de88efa8ebcaf1250.png);
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: cover;
    margin: 0px;
    padding: 0px;
    height: 4455px;
}
.left{
    display: inline-block;
    position: absolute;
    left: 34px;
    top: 20px;

}
.left img{
    width: 70px;
    margin-left: 5px;
}
.mid{
    display: block;
    width: 60%;
    margin: 29px auto;
}
.right{
    display: inline-block;
    position: absolute;
    right: 34px;
    top: 43px;
}
.navbar{
    display: inline-block;
}
.navbar li{
    display: inline-block;
    font-size: 150%;
    word-spacing: 1px;
    text-decoration: none;
}
.navbar li a{
    color: rgb(14, 206, 72);
    text-decoration: none;
    font-family: 'Epilogue', sans-serif;
    padding: 34px 4px;
}
.navbar li a:hover{
     text-decoration: transparent;    
     color:white;
     
}
.gym{
    font-family: 'Poppins', sans-serif;
    text-align: center;
    cursor: pointer;
    color: white;
}
.btn{
    margin: 0px 9px;
    background-color: black;   
    border: none;
    border-radius: 15px;
    font-family: 'Epilogue', sans-serif;
    color: rgb(14, 206, 72);
    font-size: medium;
    padding: 4px 14px;
    cursor: pointer;

}
.btn:hover{
    background-color:white;
    color: black;
}
form{
    text-align: center;
    margin-top: 200px;
    
}
.frm{
    text-align: center;
    border: none;
    border-radius: 150px;
    size: 50px;
    margin: 5px;
    color: black;
    width: 300px;
    height: 27px;
    font-family: 'Epilogue', sans-serif;
    padding: initial;
}
img:hover{
    cursor: pointer;
}
