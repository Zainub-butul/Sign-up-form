# Sign-up-form
An interactive sign up page for taking inputs from the user such as username and password etc with the submit button 

******Index.html******

<!DOCTYPE html>
<html len="en" and dir="Itr">

<head>
  <meta charset="utf-8">
  <title>Sign up</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <form class="box" action="login.html" method="POST"></form>
<form action="action_page.php" style="border:1px solid #ccc">
  <div class="container">
    <h1>Sign Up</h1>
    <p>Please fill in this form to create an account.</p>
    <hr>

    <label for="Username"><b>User Name</b></label>
    <input type="text" placeholder="Enter Your Full Name" name="email" required>

    <label for="psw"><b>Password</b></label>
    <input type="password" placeholder="Enter Password" name="psw" required>


    <label>
      <input type="checkbox" checked="checked" name="remember" style="margin-bottom:15px"> Remember me
    </label>

   

    <div class="clearfix">
      
      <button type="submit" class="signupbtn">Submit</button>


    </div>
  </div>
  </form>
</body>
