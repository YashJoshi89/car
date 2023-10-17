# car
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Cars Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }
        h1 {
            margin: 0;
        }
        nav {
            background-color: #444;
            padding: 10px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 10px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .car-image {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to the Cars Website</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#models">Models</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about">
            <h2>About Us</h2>
            <p>Welcome to our car website. We are passionate about cars and here to share our knowledge and passion with you.</p>
        </section>
        <section id="models">
            <h2>Popular Car Models</h2>
            <div>
                <h3>Car Model 1</h3>
                <img class="car-image" src="car1.jpg" alt="Car Model 1">
                <p>Description of Car Model 1 goes here.</p>
            </div>
            <div>
                <h3>Car Model 2</h3>
                <img class="car-image" src="car2.jpg" alt="Car Model 2">
                <p>Description of Car Model 2 goes here.</p>
            </div>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <p>If you have any questions or would like to get in touch with us, please email us at <a href="mailto:info@carswebsite.com">info@carswebsite.com</a>.</p>
        </section>
    </div>
</body>
</html>
