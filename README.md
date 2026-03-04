<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saras Dairy - Pattya Nirjharna</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }

        /* Header */
        header {
            background-color: #0056b3; /* Deep Blue */
            color: white;
            padding: 1rem 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        header p {
            margin: 5px 0 0;
            font-size: 1.1rem;
            font-weight: 300;
        }

        /* Navigation */
        nav {
            background-color: #f4f4f4;
            padding: 10px;
            text-align: center;
        }

        nav a {
            text-decoration: none;
            color: #333;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #0056b3;
        }

        /* Hero Section */
        .hero {
            background-color: #e3f2fd; /* Light Blue */
            padding: 50px 20px;
            text-align: center;
        }

        .hero h2 {
            color: #0056b3;
            font-size: 2rem;
        }

        .btn {
            background-color: #28a745; /* Green */
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            display: inline-block;
            margin-top: 10px;
        }

        /* About Section */
        .container {
            max-width: 1100px;
            margin: auto;
            padding: 20px;
        }

        .about {
            text-align: center;
            padding: 40px 0;
        }

        .owner-badge {
            background-color: #fff3cd;
            border: 1px solid #ffeeba;
            padding: 15px;
            display: inline-block;
            margin-top: 20px;
            border-radius: 8px;
        }

        /* Products Grid */
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            padding: 40px 0;
            background-color: #fafafa;
        }

        .product-card {
            background: white;
            border: 1px solid #ddd;
            width: 300px;
            margin: 15px;
            padding: 20px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .product-card h3 {
            color: #0056b3;
        }

        /* Contact Section */
        .contact {
            background-color: #333;
            color: white;
            padding: 40px 20px;
            text-align: center;
        }

        .contact h2 {
            color: #fff;
        }

        .contact-info {
            font-size: 1.2rem;
            margin-top: 20px;
        }

        .contact-info a {
            color: #4da6ff;
            text-decoration: none;
        }

        /* Footer */
        footer {
            background-color: #222;
            color: #aaa;
            text-align: center;
            padding: 10px;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Saras Dairy</h1>
        <p>Pattya Nirjharna BMC</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <h2>Pure & Fresh Milk for Your Family</h2>
        <p>Experience the taste of purity delivered straight from our farm to your home.</p>
        <a href="#contact" class="btn">Order Now</a>
    </section>

    <!-- About Section -->
    <section id="about" class="container about">
        <h2>About Saras Dairy</h2>
        <p>Welcome to Saras Dairy, a trusted name in the Pattya Nirjharna community. We are committed to providing high-quality, hygienic, and nutritious dairy products. Our milk is sourced from the best local farmers and processed with care to ensure it reaches your glass fresh every morning.</p>
        
        <div class="owner-badge">
            <strong>Proprietor:</strong> Mahendra Sharma
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="container products">
        <div class="product-card">
            <h3>Fresh Milk</h3>
            <p>Available in Cow and Buffalo varieties. Rich in calcium and protein.</p>
        </div>
        <div class="product-card">
            <h3>Homemade Curd</h3>
            <p>Set daily for the perfect texture and taste. Great for digestion.</p>
        </div>
        <div class="product-card">
            <h3>Pure Ghee</h3>
            <p>Traditional desi ghee made from fresh cream. Aromatic and healthy.</p>
        </div>
        <div class="product-card">
            <h3>Fresh Paneer</h3>
            <p>Soft, fresh paneer made in-house every morning.</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Ready to order? Call us today!</p>
        
        <div class="contact-info">
            <p>📞 <strong>Call 1:</strong> <a href="tel:+918094380773">+91 80943 80773</a></p>
            <p>📞 <strong>Call 2:</strong> <a href="tel:+919414625511">+91 94146 25511</a></p>
            <p>📍 <strong>Location:</strong> Pattya Nirjharna, BMC Area</p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2023 Saras Dairy. All Rights Reserved.</p>
    </footer>

</body>
</html>
