# YTRS-HUB
YTRS Hub
<br> 
<h1><i><b>Hi guys welcome to YTRS!</b><i></i></h1>
<h2></h2>
<body>

<br>
<br>
<a href="#YTRS Team Info">YTRS Team Info</a> | <a href="#Comps and Payments">Comps and Payments</a> | <a href="#Youtube">Youtube</a> 
<br>
<br>
</body>
</html>
HTML alone can't do this you need some other language in backend to check password. Or you can use javascript which will verify password in frontend but you have to specify password in the code itself only if you are doing it for fun. Otherwise for developing web app with login page you need a backend language such as php or python and database such as mysql or mariadb to store passwords.

Sample code
You need to create two files one for your login form (login.html) and another to redirect after right password is entered (welcome.html).

This code is for login.html

    <!DOCTYPE html>
<html>
<head>
    <title>Login page</title>
</head>
<body>
<form>
    <label for="pswd">Enter your password: </label>
    <input type="password" id="pswd">
    <input type="button" value="Submit" onclick="checkPswd();" />
</form>
<!--Function to check password the already set password is admin-->
<script type="text/javascript">
    function checkPswd() {
        var confirmPassword = "admin";
        var password = document.getElementById("pswd").value;
        if (password == confirmPassword) {
             window.location="welcome.html";
        }
        else{
            alert("Passwords do not match.");
        }
    }
</script>
</body>
</html>



