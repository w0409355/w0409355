# w0409355

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <link rel="stylesheet" type="text/css" href="contactPage.css">
    <title>Contact Page</title>
</head>
<body>
<div>
    <header >
        <!--<div class="headerDiv">
            <marquee behavior="alternate">Welcome to my Contact Site.</marquee>
        </div>-->
    </header>
</div>


<div class="commonHeaders">
    <div class="nameDiv">
        <h2>Harshitha Reddy</h2>
    </div>
    <div class="navDiv">
        <nav>

            <ul class="navOptions">

                <li class="navLi"><a class="active" href="contactPage.html">Contact Me</a></li>
                <li class="navLi"><a href="#">about</a></li>
                <li class="navLi"><a href="#">Blog</a></li>
                <li class="navLi"><a href="contactPage.html">Home</a></li>

            </ul>

        </nav>
    </div>
</div>


<div class="form-group formInputs">
    <fieldset>
        <legend class="legend">Contact Me</legend>
    <label for="firstName">First Name:</label>
    <input type="text" class="form-control" id="firstName" >
    <label for="lastName">Last Name:</label>
    <input type="text" class="form-control" id="lastName" >
    <label for="email">Email Address:</label>
    <input type="text" class="form-control" id="email" >
    <label for="phoneNum">Phone Number:</label>
    <input type="text" class="form-control" id="phoneNum" >
    <label for="address">Address:</label>
    <input type="text" class="form-control" id="address" >
    <label for="country">Country:</label>
    <select class="bootstrap-select form-control" id="country" >
        <option hidden>Select one</option>
        <option >Canada</option>
        <option >India</option>
        <option >Australia</option>
        <option >United States</option>
    </select>
    <label >How do you know about this website:</label>
    <div class="checkbox">
        <label><input type="checkbox" value="">Through Social Media</label>
    </div>
    <div class="checkbox">
        <label><input type="checkbox" value="">Browsing</label>
    </div>
    <label for="comment">Comment:</label>
    <textarea class="form-control" rows="5" id="comment"></textarea><br>
    <button type="submit" class="btn btn-primary button" >Send Over</button>
    </fieldset>
</div>
<footer class="page-footer">

    <div class="footer-copyright text-center py-3">© 2018 Copyright:Harshitha Reddy
    </div>

</footer>
</body>
</html>
