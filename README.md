# oibsip_l1t1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> My Landing Page</title>
    <style>
        /* Reset some default styles */
        body, h1, h2, p {
            margin: 0;
            padding: 0;
        }

        /* Set a background color and text color */
        body {
            background-color: #f5f5f5;
            font-family: Arial, sans-serif;
            color: #333;
        }

        /* Header Styles */
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
        }

        /* Navigation Styles */
        nav {
            text-align: center;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 20px;
            font-size: 1.2rem;
        }

        /* Hero Section Styles */
        .hero {
            background-image: url("image-4.jpg");
            background-size: cover;
            background-position: center;
            text-align: center;
            padding: 100px 0;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            color:white;
        }

        .hero p {
            font-size: 1.2rem;
            color:white;

        }

        /* Feature Section Styles */
        .features {
            display: flex;
            justify-content: space-around;
            padding: 80px 0;
            background-color: #fff;
        }

        .feature {
            text-align: center;
        }

        .feature i {
            font-size: 2rem;
            color: #333;
        }

        /* Footer Styles */
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Services</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <div class="hero">
        <h1>Welcome to My Landing Page</h1>
        <p>Books were safer than other people anyway.</p>
    </div>

    <div class="features">
        <div class="feature">
            <i class="fa fa-check-circle"></i>
            <h2>Biography</h2>
            <p> 'Life-writing'</p>
        </div>
        <div class="feature">
            <i class="fa fa-check-circle"></i>
            <h2>Fiction</h2>
            <p>literature created from the imagination</p>
        </div>
        <div class="feature">
            <i class="fa fa-check-circle"></i>
            <h2>Memoir</h2>
            <p> Author's real life. </p>
        </div>
    </div>

    <footer>
        &copy; 2023 Classic Book Landing Page
    </footer>
</body>
</html>
