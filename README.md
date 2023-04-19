# Simple-Login-Page-
This is a simple  login page created by  using html and css.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>login page</title>
    <style>
        body{
            margin:0;
            padding:0;
            background-color:#6adb95ea ;
            font-size: medium;
            font-family:Arial, Helvetica, sans-serif;
        }
          #login{
          width: 500px;   
        overflow: hidden;
        margin: auto;
        margin: 20 0 0 450px;
        padding: 80px;
        background :#234639;

        border-radius: 25px;
            
        
          }
          label{
            color:chartreuse;
            
          }
          h4{
            color:blueviolet;
        
            font-size:0.5cm;
            padding: 10px;
            
          } 
          #mybutton{
            color:black;
            background-color:rgb(195, 0, 255);
          }
          span{
            color:white;
          }
          a{
            float:center;
            color:rgb(42, 95, 165);
          }
          
    </style>
</head>
<body>

    <h4 align="center"><u>Login Page</u> </h4>
    <form id="login" method="post" action="backend.php">
    <div>
        <label for="Email id" name="Email id"  ><b>Email id:</b></label><br>
        <input type="email" id="Emailid" placeholder="enter your email" size="25" required/><br><br>
        
    </div>
    <div>

    </div>
    <div>

    </div>
    <div>
       <label for="password" name="password"><b>password:</b ></label><br>
        <input type="password" name="password " placeholder="enter your password" id="psd" size="20" required/>
    </div>
    <br>
    <input type="button" id="mybutton" name="button" value="Login">
    <br><br>
    <input type="checkbox" name="mycheck" id="check">
    <span>Remember me</span><br><br>
    forgot<a href="#" target="blank">password</a>
    </form>

</body>
</html>
