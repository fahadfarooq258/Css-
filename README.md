<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
    
    <style>
        body{
            margin: 0;
            background-color: #f4f4f4;
        }
        ul{
            color:rgb(152, 136, 116);
        }
        .nav{
            text-align: center;
            background-color: rgb(243, 136, 5);
            padding: 16px;
            border-radius: 122px;
        }
        .registration-form {
            justify-content: center;
            background-color: white;
            padding: 20px;
            border-color: #5f0bf0;
            border-radius: 5px;
            box-shadow: 0 -5px 1px rgb(255, 172, 19);
            width: 300px; 
            margin: auto;
            border: 0 solid rgba(236, 169, 23, 0.82);
            padding: 10px;
        }

        .registration-form h2 {
            text-align: center;
            margin-bottom: 20px;
        }

        .registration-form input[type="text"],
        .registration-form input[type="email"],
        .registration-form input[type="password"],
        .registration-form select{
            width: 90%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #382222;
            border-radius: 5px;
        }

        .registration-form input[type="name"] {
            width: 40%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #382222;
            border-radius: 5px;
        }

        .registration-form label {
            font-size: 12px;
        }

        .registration-form button {
            width: 100%;
            padding: 15px;
            background-color: rgb(255, 172, 19);
            border: none;
            border-radius: 5px;
            color: white;
            font-size: 16px;
        }

        .registration-form button:hover {
            background-color: rgb(243, 136, 5);
        }
    </style>

</head>

<body>
    <form>
    <ul>
        <li>NAME : Shahzaib</li>
        <li>CLASS : Batch.15</li>
        <li>COURSE : Web Development</li>
        <li>TEACHER NAME : Sir.Rizwan Bhatti</li>
    </ul>

    <div class="nav">
        <a href="index.html" style="color: white; margin: 50px;">HOME</a>
        <a href="resitration.html" style="color: white; margin: 50px;">Registration</a>
    </div><br><br>
</form>

    <form class="registration-form" >
  
        <h2>Responsive Registration Form</h2>

        <input type="email" placeholder="Email" required>
        <input type="password" placeholder="Password" required>
        <input type="password" placeholder="Re-type Password" required>
        <input type="name" placeholder="First Name" required>
        <input type="name" placeholder="Last Name" required>
      
        <div>
            <label><input type="radio" name="gender" value="male"> Male</label>
            <label><input type="radio" name="gender" value="female"> Female</label>
        </div>

        <select required>
            <option value="" disabled selected>Select a country</option>
            <option value="india">India</option>
            <option value="usa">USA</option>
            <option value="uk">Dubai</option>
            <option value="uk">pakistan</option>
            <option value="uk">Uk</option>
        </select>

        <div>
            <label><input type="checkbox" required> I agree with terms and conditions</label>
        </div>

        <div>
            <label><input type="checkbox"> I want to receive the newsletter</label>
        </div><br>

        <button type="submit">Register</button>
    
    </form>

</body>
</html>
