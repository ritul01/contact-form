# contact-form
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact form</title>
  <!--  <link rel="stylesheet" href="contact.css">   -->
</head>
<body>
    <div class="container">
        <form action="">
            <h1 class="main_heading">Contact Form</h1>
            <hr>
            <p>Name: <input type="text" required placeholder="example"></p>
            <p>D.O.B: <input type="date" name="D.O.B" id="D.O.B" required></p>
            <fieldset>
                <legend>Gender</legend>
            <p>
                Male <input type="radio" name="gender" id="male" required>
                Female <input type="radio" name="gender" id="female" required>
            </p>
            </fieldset>
            <p>Adderss: <textarea name="adderss" id="adderss" cols="100" rows="10" required placeholder="Enter your aderss"></textarea></p>
            <p>Email: <input type="email" name="email" id="email" required placeholder="exampl@gmail.com"></p>
            <p>Phone No.: <input type="number" name="Phone number" id="number" required placeholder="6546876878"></p>
            <p>Aadhar No.: <input type="number" name="aadhar" id="aadhar" required placeholder="1234567891234596"></p>
            <p><input type="submit" value="Save"></p>
        </form>
    </div>
</body>
</html>
