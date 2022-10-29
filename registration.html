
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8"/>
    <title>Registration</title>
    <link rel="stylesheet" href="style.css"/>
</head>
<body>
<?php
    require('db.php');
    // When form submitted, insert values into the database.
    if (isset($_REQUEST['username'])) {
        // removes backslashes
        $username = stripslashes($_REQUEST['username']);
        //escapes special characters in a string
        $username = mysqli_real_escape_string($con, $username);
        $email    = stripslashes($_REQUEST['email']);
        $email    = mysqli_real_escape_string($con, $email);
         $mobile_no    = stripslashes($_REQUEST['mobile_no']);
        $mobile_no    = mysqli_real_escape_string($con, $mobile_no);
        $password = stripslashes($_REQUEST['password']);
        $password = mysqli_real_escape_string($con, $password);
        
        $query    = "INSERT into `users` (username, email, mobile_no, password)
                     VALUES ('$username',  '$email', '$mobile_no''" . md5($password) . "')";
        $result   = mysqli_query($con, $query);
        if ($result) {
            echo "<div class='form'>
                  <h3>You are registered successfully.</h3><br/>
                  <p class='link'>Click here to <a href='login.php'>Login</a></p>
                  </div>";
        } else {
            echo "<div class='form'>
                  <h3>Required fields are missing.</h3><br/>
                  <p class='link'>Click here to <a href='registration.php'>registration</a> again.</p>
                  </div>";
        }
    } else {
?>
    
    <div class= "container">
        <div class="row">
            <div class="col-md-3">
 
            </div>
            <div class="col-md-6 main">
                <form action="/signup" method="POST"></form>
                <h2>Registration Form</h2>
                <input type="text" class="box" id="username" name="username" placeholder="Name" required>
                <br>
                <input type="text" class="box" id="email" name="email" placeholder="Email" required>
                <br>
                <input type="text" class="box" id="mobile_no" name="mobile_no" placeholder="Mobile" required>
                <br>
                <input type="text" class="box" id="password" name="password" placeholder="password" required>
                <br>
                <input type="submit" value="submit" id="submit" />
            </form>
            </div>
            <div class="col-md-3">
 
            </div>
        </div>
    </div>

<?php
    }
?>
</body>
</html>
