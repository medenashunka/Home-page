# Home-page
This is index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home page Login/register</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
   <dev class="hero"
    <div class="form-box"></div>
</dev>

<div class="center">
            <h1>Login</h1>
<form method="post">
    <div class="txt_field">
        <input type="text" required>
        <span></span>
        <label>Username</label>
    </div>
    <div class="txt_field">
        <input type="password" required>
        <span></span>
        <label>Password</label>
    </div>
    <div class="password"></div>
    <input type="Submit" value="login">
    <div class="signup_link">
        <h2>Not a member?</h2> <a href="#">Sign up</a>
    </div>
</form>


</div>




    
</body>
</html>

This is the style.css
*{
    margin: 0;
    padding: 0;
}
body{
    
    height: 100vh;
    background-image: url(/images/pexels-pixabay-221433.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    
}
.center{
    position: absolute;
    top: 50%;
    left: 50%;
    transform:translate(-50%, -50%) ;
    width: 400px;
    background: rgb(183, 0, 255);
    border-radius: 10px;
    background:transparent
}
.center h1{
    text-align: center;
    padding: 0 0 20px 0;
    border-bottom: 1px solid rgb(0, 0, 0);
}
.center form{
    padding: 0 40px;
    box-sizing: border-box;
}
form .txt_field{
    position: relative;
    border-radius: 2px solid #ffffff;
    margin: 30px 0;
}
.txt_field input{
    width: 100%;
    padding: 0 5px;
    height: 40px;
    font-size: 16px;
    border: none;
    background: none;
    outline: none;
}
.txt_field label{
    position: absolute;
    top: 50%;
    left: 5px;
    color: #ffffff;
    transform: translateY(-50%);
    font-size: 16px;
    pointer-events: none;
    transition: .5s;
}
.txt_field span::before{
    content:'';
    position: absolute;
    top: 40px;
    left: 0;
    width: 100%;
    height: 2px;
    background:#000000 ;
    transition: .5s;
}
.txt_field input:focus ~ label,
.txt_field input:valid ~ label{
    top: -5px;
    color: #000000;

}
.txt_field input:focus ~ span::before,
.txt_field input:valid ~ span::before{
    width: 100%;
}
.pass{
    margin: -5px 0 20 px 5 px;
    color: black;
    cursor: pointer;
}
.pass:hover{
    text-decoration: underline;
}
input[type="Submit"]{
    width: 100%;
    height: 50px;
    border: 1px solid;
    background:#ffffff ;
    border-radius: 25px;
    font-size: 18px;
    color: #000000;
    font-weight: 700;
    cursor:pointer;
    outline: none;
}
input[type="Submit"]:hover{
    border-color: rgb(255, 255, 255);
    transition: .5s;
}
.signup_link{
    margin: 3px 0;
    text-align: center;
    font-size: 16px;
    color: rgb(0, 0, 0);
}
ignup_link{
    color: rgb(0, 47, 255);
    text-decoration: none;
}
.signup_link a:hover{
    text-decoration: underline;
}


