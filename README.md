<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 50px 20px;
            text-align: center;
        }
        .hero h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        .hero p {
            font-size: 1.2em;
        }
        .cta-button {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
        }
        .cta-button:hover {
            background-color: #218838;
        }
        section {
            padding: 40px 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        .features {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .feature {
            flex: 1;
            min-width: 200px;
            margin: 10px;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>
    <header class="hero">
        <h1>Welcome to My Awesome Product</h1>
        <p>Discover how we can change your life.</p>
        <button class="cta-button" onclick="alert('Thank you for your interest!')">Get Started</button>
    </header>
    
    <section>
        <h2>Why Choose Us?</h2>
        <div class="features">
            <div class="feature">
                <h3>Feature 1</h3>
                <p>Amazing benefits that solve your problems.</p>
            </div>
            <div class="feature">
                <h3>Feature 2</h3>
                <p>Easy to use and highly effective.</p>
            </div>
            <div class="feature">
                <h3>Feature 3</h3>
                <p>Reliable support whenever you need it.</p>
            </div>
        </div>
    </section>
    
    <footer>
        <p>&copy; 2023 My Company. All rights reserved.</p>
    </footer>
    
    <script>
        // Simple JS for interactivity (e.g., button click)
        document.querySelector('.cta-button').addEventListener('click', function() {
            alert('CTA clicked! In a real page, this could lead to a form or signup.');
        });
    </script>
</body>
</html>
