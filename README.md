<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Car Registration</title>
    <link rel="icon" type="image/x-icon" href="/IG.jpeg">
    <style>
            body{
                background-color: skyblue;
                margin: 70px;
            }
            .hello{
                color: darkred;
                font-family: Georgia, 'Times New Roman', Times, serif;
            }
        </style>
</head>
<body>
    <div>
        <h1 class="hello">Car Registration</h1>
    </div>
    <div>
        <h2 class="hello">Names and Contact</h2>
        <form>
            <label for="fname">First Name</label><br>
            <input type="text" name="First Name" id="fname" placeholder="enter your first name..."><br><br>
            <label for="lname">Last Name</label><br>
            <input type="text" name="Last Name" id="lname" placeholder="enter your last name..."><br><br>
            <label for="email">Email</label><br>
            <input type="email" name="your email" id="email" placeholder="enter your email..."><br><br>
            <label for="phone">Tel</label><br>
            <input list="code" name="your phone code" size="3">
            <datalist id="code">
                <option value="+1">+1</option>
                <option value="+250">+250</option>
            </datalist>
            <input type="tel" name="telephone number" id="number" placeholder="781674354"><br>
            <label for="country">country</label><br>
        </form>
    </div>
    <div>
        <h2 class="hello">Adress</h2>
        <form>
            <label for="from">Country</label>
            <select name="country" id="from">
                <option value="Rwanda">Rwanda</option>
                <option value="USA">USA</option>
            </select>
            <label for="where">State</label>
            <select name="state" id="where">
                <option value="California">California</option>
                <option value="New York">New York</option>
                <option value="Ohio">Ohio</option>
            </select>
            <label for="fromwhere">city</label>
            <select name="state" id="fromwhere">
                <option value="Los angels">Los Angels</option>
                <option value="San Francisco">San Francisco</option>
                <option value="Manhattan">Manhattan</option>
                <option value="brooklyn">Brooklyn</option>
                <option value="Cleveland">Cleveland</option>
            </select>
        </form>
    </div>
</body>
</html>
