# codeHtml.html

```markup
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Landing Page</title>
    <style>
        body {
            font-family: -apple-system, system-ui, sans-serif;
            margin: 0;
            padding: 0;
            background: #f5f5f5;
        }
        .hero {
            background: linear-gradient(135deg, #6e8efb, #a777e3);
            color: white;
            padding: 4rem 2rem;
            text-align: center;
        }
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }
        .hero p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        .features {
            max-width: 1200px;
            margin: 4rem auto;
            padding: 0 2rem;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        .feature {
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body>
    <div class="hero">
        <h1>Welcome to Our Platform</h1>
        <p>The next generation of web development starts here</p>
    </div>
    <div class="features">
        <div class="feature">
            <h2>Easy to Use</h2>
            <p>Our platform is designed with simplicity in mind. Get started in minutes.</p>
        </div>
        <div class="feature">
            <h2>Powerful Features</h2>
            <p>Access advanced tools and features to boost your productivity.</p>
        </div>
        <div class="feature">
            <h2>24/7 Support</h2>
            <p>Our dedicated team is here to help you succeed.</p>
        </div>
    </div>
</body>
</html>
```