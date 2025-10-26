<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>khaleefa Mai Na'ura | Web Design & Development Course</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
        }


        body {
            background: linear-gradient(to bottom, #0a0a0a, #2c3e50);
            color: #fff;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 50px;
            background: #000;
        }

        header h1 {
            color: #ff4500;
            font-size: 28px;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 25px;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
            font-weight: bold;
            transition: 0.3s;
        }

        nav ul li a:hover {
            color: #ff4500;
        }

        .search-box {
            display: flex;
            align-items: center;
            gap: 5px;
        }

        .search-box input[type="text"] {
            padding: 5px 10px;
            border: 1px solid #ff4500;
            border-radius: 3px;
            background: transparent;
            color: #fff;
        }

        .search-box input[type="submit"] {
            background: #ff4500;
            border: none;
            color: #fff;
            padding: 6px 12px;
            border-radius: 3px;
            cursor: pointer;
        }

        .main-content {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            padding: 80px 50px;
        }

        .text-section {
            max-width: 55%;
        }

        .text-section h2 {
            font-size: 40px;
            color: #fff;
        }

        .text-section span {
            color: #ff7b00;
        }

        .text-section p {
            margin: 20px 0;
            line-height: 1.6;
            color: #ccc;
        }

        .text-section button {
            padding: 10px 20px;
            background: #ff4500;
            border: none;
            color: #fff;
            border-radius: 4px;
            cursor: pointer;
            font-weight: bold;
        }

        .login-box {
            background: rgba(0, 0, 0, 0.6);
            padding: 30px;
            width: 280px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(255, 69, 0, 0.5);
        }

        .login-box h3 {
            text-align: center;
            margin-bottom: 20px;
            color: #fff;
        }

        .login-box input[type="email"],
        .login-box input[type="password"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: none;
            border-bottom: 2px solid #ff4500;
            background: transparent;
            color: #fff;
            outline: none;
        }

        .login-box input[type="submit"] {
            width: 100%;
            padding: 10px;
            background: #ff4500;
            color: #fff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-weight: bold;
        }

        .login-box p {
            margin-top: 10px;
            text-align: center;
            font-size: 14px;
        }

        .login-box a {
            color: #ff7b00;
            text-decoration: none;
        }

        .login-box a:hover {
            text-decoration: underline;
        }
    </style>
</head>

<body>

    <header>
        <h1>4Tech Technology</h1>
        <nav>
            <ul>
                <li><a href="#">HOME</a></li>
                <li><a href="#">ABOUT</a></li>
                <li><a href="#">SERVICE</a></li>
                <li><a href="#">DESIGN</a></li>
                <li><a href="#">CONTACT</a></li>
            </ul>
        </nav>
        <div class="search-box">
            <input type="text" placeholder="type To text">
            <input type="submit" value="search">
        </div>
    </header>

    <section class="main-content">
        <div class="text-section">
            <h2>Web Design & <span>Development</span> Course</h2>
            <p>
                Khaleefa Mai Na'ura is a Computer Science student who began building his career in 2018 to provide
                solutions in web development, IT solutions, Hardware maintenance, networking and digital services.
            </p>
            <button>JOIN us</button>
        </div>

        <div class="login-box">
            <h3>Login Here</h3>
            <form>
                <input type="email" placeholder="Enter Email Here" required>
                <input type="password" placeholder="Enter password Here" required>
                <input type="submit" value="Login">
                <p>Don't have an account? <a href="#">Sign up here</a></p>
                <p><a href="#">Log in with</a></p>
            </form>
        </div>
    </section>

</body>

</html>
