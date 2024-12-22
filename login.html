<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MSRIT Login</title>
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .login-container {
            background: #ffffff;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
            padding: 20px 30px;
            border-radius: 8px;
            width: 100%;
            max-width: 400px;
            text-align: center;
        }

        .login-container img {
            max-width: 80px;
            margin-bottom: 10px;
        }

        .login-container h2 {
            color: #343a40;
            margin-bottom: 10px;
        }

        .login-container h3 {
            color: #6c757d;
            font-size: 18px;
            margin-bottom: 20px;
        }

        .form-group {
            margin-bottom: 15px;
            text-align: left;
        }

        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }

        .form-group input {
            width: 100%;
            padding: 10px;
            border: 1px solid #ced4da;
            border-radius: 5px;
            font-size: 16px;
        }

        .form-group input:focus {
            outline: none;
            border-color: #007bff;
            box-shadow: 0 0 5px rgba(0, 123, 255, 0.25);
        }

        .submit-btn {
            width: 100%;
            padding: 10px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
        }

        .submit-btn:hover {
            background-color: #0056b3;
        }
x
        .footer {
            margin-top: 20px;
            font-size: 14px;
            color: #6c757d;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <img src="logo.jpg" alt="MSRIT Logo" height="150px" width="1800px">
        <h2>MS Ramaiah Institute of Technology</h2>
        <h3>Student Login</h3>
        <form method="post" action="login.php">
    
            <div class="form-group">
                <label for="usn">USN (University Seat Number)</label>
                <input type="text" id="usn" name="usn" placeholder="Enter your USN" required>
            </div>
            <div class="form-group">
                <label for="dob">Date of Birth</label>
                <input type="date" id="dob" name="dob" required>
            </div>
            <button type="submit" class="submit-btn" name="login_btn">Login</button>
        </form>
        <div class="footer">
            <p>&copy; 2024 MS Ramaiah Institute of Technology. All Rights Reserved.</p>
        </div>
    </div>
</body>
</html>
<?php
$con = mysqli_connect("localhost", "root", "", "websitelogin");     
if (!$con) {
    die("Connection failed: " . mysqli_connect_error()); 
}

if (isset($_POST['login_btn'])) {
    $usn = $_POST['usn'];
    $dob = $_POST['dob'];

    
    $sql = "SELECT * FROM logindetails WHERE usn = '$usn'";
    $result = mysqli_query($con, $sql);

    if ($result && mysqli_num_rows($result) > 0) {
        while ($row = mysqli_fetch_assoc($result)) {
            $resultdob = $row["dob"];
            if ($dob == $resultdob) {
                header('Location: home.html');
                exit(); 
            } else {
                echo "<script>
                alert('Login Unsuccessful: Incorrect DOB');
                </script>";
            }
        }
    } else {
        echo "<script>
        alert('Login Unsuccessful: USN not found');
        </script>";
    }
}

mysqli_close($con); 
?>
