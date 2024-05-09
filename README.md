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



    <html>
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
  


