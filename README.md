# thepioneersnest.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>
    <style>
        /* Basic reset and typography */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
            background-color: #f9f9f9;
        }

        /* Navigation Bar */
        header {
            background-color: #2c3e50;
            color: #fff;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            margin: 0;
            font-size: 1.5rem;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin-left: 15px;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Main Content Container */
        .container {
            max-width: 800px;
            margin: 30px auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        /* Hero / Welcome Section */
        .hero {
            text-align: center;
            padding: 40px 20px;
            background-color: #ecf0f1;
            border-radius: 6px;
            margin-bottom: 20px;
        }

        .hero h2 {
            color: #2c3e50;
            margin-top: 0;
        }

        /* Button style */
        .btn {
            display: inline-block;
            background-color: #3498db;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 4px;
            font-weight: bold;
            margin-top: 15px;
        }

        .btn:hover {
            background-color: #2980b9;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            font-size: 0.9rem;
            color: #7f8c8d;
        }
    </style>
</head>
<body>

    <!-- Header & Navigation -->
    <header>
        <h1>My Website</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Main Content -->
    <div class="container">
        <!-- Welcome / Hero Section -->
        <section class="hero">
            <h2>Welcome to My First Webpage!</h2>
            <p>This is a super clean, minimal website built completely from scratch using HTML and CSS.</p>
            <a href="#about" class="btn">Learn More</a>
        </section>

        <!-- About Section -->
        <section id="about" style="padding: 20px 0;">
            <h3>About This Project</h3>
            <p>Coding a website doesn't have to be complicated. This page demonstrates how structure (HTML) and style (CSS) come together to build a functional design. You can open this file directly in any browser to see it in action!</p>
        </section>

        <hr style="border: 0; border-top: 1px solid #eee;">

        <!-- Contact Section -->
        <section id="contact" style="padding: 20px 0;">
            <h3>Get In Touch</h3>
            <p>Want to build something together? Send me an email or find me on social media.</p>
            <p><strong>Email:</strong> hello@example.com</p>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 My Simple Website. Built with care.</p>
    </footer>

</body>
</html>
