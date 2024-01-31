<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hassan's Cuisine</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        .header {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
        }

        .navbar {
            background-color: #555;
            overflow: hidden;
        }

        .navbar a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }

        .navbar a:hover {
            background-color: #777;
        }

        .content {
            padding: 15px;
            text-align: center;
        }

        .menu-item {
            display: inline-block;
            margin: 10px;
        }

        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .copyright {
            margin: 5px;
        }

        .weather {
            text-align: right;
            margin-right: 15px;
        }

        .time {
            text-align: left;
            margin-left: 15px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>KHIZAR CUISINE</h1>
    </div>
        <div class="navbar">
            <a href="#home">Home</a>
            <a href="#menu">Menu</a>
            <a href="#about">About</a>
            <a href="#timing">Timing</a>
            <a href="#contact">Contact Us</a>
        </div>

    <div class="content">
        <div class="menu-item">
            <img src="burger.png" alt="Burger" width="200px" height="200px">
            <p>Burgers</p>
        </div>
        <div class="menu-item">
            <img src="pizza.png" alt="Pizza" width="200px" height="200px">
            <p>Pizzas</p>
        </div>
        <div class="menu-item">
            <img src="2.png" alt="Burger" width="200px" height="200px">
            <p>Pizza Deal</p>
        </div>
        <div class="menu-item">
            <img src="3.png" alt="Burger" width="200px" height="200px">
            <p>Burger Deal</p>
        </div>

    </div>

    <div class="footer">
        <p class="copyright">&copy; 2023 KHIZAR CUISINE</p>
    </div>
</body>
</html>
