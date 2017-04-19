# learning
<html>
<head>
<style>
.b1{
	border:2px solid green;
	padding:20px;
	size:auto;
	background:wheat;
	text:blue; 
}
.marquee{
		behaviour="scroll" height="20px;
}
</style>
<title>
</title>
</head>
<body class="b1">
<marquee class="marquee">REGISTRATION STARTED!!!</marquee><br/><br/>
<form action="sign_up_details.php" method="post">
FIRST NAME : <br/><input type="text" name="first_name" placeholder=" enter first name "required="required"/><br/><br/>
LAST NAME : <br/><input type="text" name="last_name" placeholder=" enter last name "required="required"/><br/><br/>
EMAIL :<br/><input type="text" name="email" placeholder=" enter email"required="required"/><br/><br/>
AGE :<br/><input type="text" name="age" placeholder=" enter age"required="required"/><br/><br/>
DOB :<br/><input type="date" name="dob"required="required"/><br/></br>
MOBILE :<br/><input type="text" maxlength="10" name="mobile" placeholder=" enter mobile"required="required"/><br/><br/>
PASSWORD :<br/><input type="password" name="pass" placeholder=" enter password"required="required"/><br/><br/>
<input type="submit" name="btn" value="SUBMIT"/>
<center><h3>ALREADY REGISTER?<a href="login_page.php" text-decoration="none"target="_blank">LOGIN HERE</a></h3></center>
</form>
</body>
</html>
