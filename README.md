# harrygsoc
practice
<html>
<head>
<title>form page</title>
<link rel="stylesheet" type="text/css" href="register.css" method="get">
</head>
<body>
<a href="port.html">HOME</a><br><br>
<hr>
<div class="box">
<h1>Registeration Form</h1>
<form id="reg" autocomplete="on" action="App.html">
<br>
<fieldset class="a1">
<legend><label>Personal Info:</label></legend><br>
FIRST NAME: <input type="text" name="name" required placeholder="enter your first name"><br><br>
LAST NAME:  <input type="text" name="surname" required  placeholder="enter your last name"><br>
</fieldset>
<BR>
<fieldset class="a2">
<legend><label>Contact Info:</label> </legend><br>
EMAIL: <input type="email" name="emailaddress"  placeholder="enter your email"><br><br>
PHONE: <input type="tel" name="phoneno" required  placeholder="enter your phone no"><br>
</fieldset>
<BR>
<fieldset class="a3">
<legend><label>Gender:</label> </legend><br>
MALE: <input type="radio" name="gender" required >
FEMALE: <input type="radio" name="gender" required>
KEEP IT PRIVATE: <input type="radio" name="gender" required><br>
<br>
</fieldset> <BR>
  <p>
  <input type="checkbox" name="checkbox" required>I have fill all details correct.</p>
  <br>
  <div class="container">
<button class="btn btn1">SUBMIT</button>
</div>
<br>
</form>
</div>
</body>
</html>
