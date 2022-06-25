<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forms</title>
</head>
<body>
    <h2>This is HTML forms tutorial</h2>
    <form action="backend.php">
        <label for="name">Name</label>
        <div>
            <input type="text" name="myName" id="name">
        </div>
        <br>
        <div>
           Role: <input type="text" name="myRole">
        </div>
        <br>
        <div>
            Email: <input type="email" name="myEmail">
        </div>
        <br>
        <div>
            Bonus: <input type="number" name="myBonus">
        </div>
        <br>
        <div>
            Are you eligible?: <input type="checkbox" name="myEligibility">
        </div>
        <br>
        <div>
            Gender: Male <input type="radio" name="myGender">
            Gender: Female <input type="radio" name="myGender">
            Gender: Other <input type="radio" name="myGender">
        </div>
        <br>
        <div>
            Write about Yourself: <br><textarea name="myText"  cols="30" rows="40"></textarea>
        </div>
        <br>
        <div>
            <input type="submit" value="Submit">
            <input type="reset" value="Reset">
        </div>
    </form>
</body>
</html>
