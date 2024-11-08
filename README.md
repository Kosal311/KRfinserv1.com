<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>KR Financial Services</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background-color: #34495e;
            overflow: hidden;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            display: inline-block;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #1abc9c;
        }
        main {
            padding: 20px;
        }
        section {
            margin-bottom: 20px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #34495e;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .services {
            display: flex;
            justify-content: space-around;
        }
        .service-box {
            background-color: white;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            width: 30%;
            text-align: center;
        }
        .service-box h3 {
            color: #2c3e50;
        }
        .service-box p {
            font-size: 14px;
            color: #7f8c8d;
        }
    </style>
</head>
<body>
    <header>
        <h1>KR Financial Services</h1>
        <p>Your Trusted Partner for Financial Growth</p>
    </header>
    
    <nav>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact Us</a>
    </nav>

    <main>
        <section id="about">
            <h2>About Us</h2>
            <p>KR Financial Services is a leading provider of financial planning, investment advisory, and wealth management services. Our goal is to provide customized solutions that help you achieve financial stability and growth. With years of experience in the industry, our team of experts is committed to delivering exceptional services to individuals and businesses alike.</p>
        </section>

        <section id="services">
            <h2>Our Services</h2>
            <div class="services">
                <div class="service-box">
                    <h3>Investment Advisory</h3>
                    <p>We offer expert advice on various investment opportunities to grow your wealth efficiently.</p>
                </div>
                <div class="service-box">
                    <h3>Financial Planning</h3>
                    <p>Our financial planning services help you structure your finances for long-term security and success.</p>
                </div>
                <div class="service-box">
                    <h3>Wealth Management</h3>
                    <p>Comprehensive wealth management services to ensure your assets are preserved and enhanced.</p>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>Have questions or need assistance? Reach out to us:</p>
            <p>Email: <a href="mailto:KRFinserv@gmail.com">KRFinserv@gmail.com</a></p>
            <p>Phone: +91 7010086463</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 KR Financial Services. All rights reserved.</p>
    </footer>
</body>
</html>
