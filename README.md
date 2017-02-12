# MyRepo-1

<!DOCTYPE html>
<html>
<head>
<title>Login Form</title>
</head>
<boby>
<h1> Register</h1>
<form>
<label for="fname"> First name:</label>
<input type="text" id="fname" placeholder="FirstName" required>
<label for="lname"> Last Name: </label>
<input type="text" id="lname" placeholder="LastName" required>
<br></br>
<label for="male">Male</label>
<input name="selectRadio" type="radio" id="male" value="maleVal" >
<label for="female">Female</label>
<input name="selectRadio" id="female" type="radio" value="femalVal" >
<label for="other">Other</label>
<input name="selectRadio" id="other" type="radio" value="otherVal">
<br></br>
<label for="emailid">Email:</label>
<input name="EmailAddress" id="emailid" type="email" placeholder="xyz@gmail.com" required>
<label for="password" > Password: </password>
<input name="pass" type="password" id="password" placeholder="*************" pattern=".{5,10}"  title="5 to 10 characters" required>
<br></br>
<lable for="BirthDate" >BirthDay: </label>
<input type="date" name="datepicking" id="BirthDate" required>
<br></br>
<label for="t&c">I agree on terms and conditions</lable >
<input type="checkbox" name="cBox" id="t&c" required>
<br></br>
<input type = "submit">
</form>
</body>

</html>
