<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Login Page</title>
    <style>
      #loginbox {
        border: solid blue 4px;
        border-radius: 20px;
        background-color: pink;
        height: 400px;
        width: 240px;
        margin-top: 65px;
        margin-right: 200px;
        margin-left: 50px;
        font-size: 30px;
      }
      #loginheading {
        text-decoration: underline;
        padding-left: 83px;
        color: red;
        padding-top: 20px;
      }
      .seconddiv {
        font-size: 15px;
        padding-top: 30px;
        padding-left: 5px;
        margin-right: 20px;
        margin-left: 40px;
        color: purple;
      }
      #firstname {
        width: 140px;
        padding-left: 5px;
        background-color: #dec1d0;
        border: solid blue 2px;
      }
      #lastname {
        width: 140px;
        padding-left: 5px;
        background-color: #dec1d0;
        border: solid blue 2px;
      }
      #password {
        border: solid blue 2px;
        width: 140px;
        padding-left: 5px;
        background-color: #dec1d0;
      }
      #submit {
        margin-left: 80px;
        margin-right: 100px;
        margin-top: 40px;
        height: 30px;
        width: 80px;
        border-radius: 20px;
        border-color: blue;
        background-color: #f5e6f1;
      }
      h1{
        font-family: cursive;
        text-align: center;
        text-decoration: underline;
        font-size: 60px;
      }
      html{
        background-color: #e5e887;
      }
    </style>
  </head>
  <body>
    <h1>Login for you</h1>
    <div id="loginbox">
      <span id="loginheading">Login</span>
      <div class="seconddiv">
        First name:<input type="Username" id="firstname" />
      </div>
      <div class="seconddiv">Last Name:<input type="text" id="lastname" /></div>
      <div class="seconddiv">
        Password :<input id="password" type="password" />
      </div>
      <div class="seconddiv">
        Re-Type :<input id="password" type="password" />
      </div>
      <input id="submit" type="submit" />
    </div>
  </body>
</html>
