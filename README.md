# heimavinna
Heimavinna



Bjarni:




Július:




Erik:


Register Codein
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>Registration</title>
</head>

<body>
<h1>Register</h1>
<form name="registration">
  <p>
    <label>Username:</label>
    <br/>
<input name="username" type="text" required><br/>
<label>Password:</label>
<br/>
<input name="password" type="text" required><br/>
<label>Email:</label>
<br/>
<input name="email" type="text" required>
<br/>
<input type="submit" value="Register">
  </p>
  <p>Already have an account? <a href="login.php">Login!</a></p>
</form>
</body>
</html>





Login Codein
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>login</title>
</head>

<body>
<h1>Log In</h1>
<form name="login_form">
<label>Username:<br/></label>
<input name="username" type="text" autofocus="autofocus" required="required"><br/>
<label>Password:<br/></label>
<input name="password" type="password" required="required"><br/>
<input type="submit" value="login">
</form>
<a href="register.php">Register</a>
</body>
</html>
