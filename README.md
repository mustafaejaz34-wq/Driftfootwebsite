<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Driftfoot - Premium Shoes</title>
    <style>
        /* Reset and base styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f9f9f9;
        }
        a {
            text-decoration: none;
            color: inherit;
        }
        /* Header */
        header {
            background-color: #000;
            color: #fff;
            padding: 1rem 2rem;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 100;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .logo {
            font-size: 1.8rem;
font-weight: bold;
            letter-spacing: 1px;
        }
        nav ul {
            list-style: none;
            display: flex;
        }
        nav ul li {
            margin-left: 2rem;
        }
        nav ul li a {
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #ccc;
        }
        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #000 0%, #333 100%);
            color: #fff;
            padding: 8rem 2rem 4rem;

   text-align: center;
            margin-top: 0;
        }
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
        }
        .btn {
            background-color: #fff;
            color: #000;
            padding: 0.8rem 2rem;
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #ccc;
        }
                /* Products Section */
        .products {
            padding: 4rem 2rem;
            text-align: center;
        }
        .products h2 {
            font-size: 2.5rem;
            margin-bottom: 2rem;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        .product {
            background-color: #fff;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
         .product:hover {
            transform: translateY(-5px);
        }
        .product img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .product h3 {
            padding: 1rem;
            font-size: 1.2rem;
        }
        /* About Section */
        .about {
            background-color: #fff;
            padding: 4rem 2rem;
            text-align: center;
        }
        .about h2 {
            font-size: 2.5rem;
            margin-bottom: 2rem;
        }
        .about p {
            max-width: 800px;
            margin: 0 auto;
            font-size: 1.1rem;
        }
        /* Footer */
        footer {
            background-color:  #000;
            color: #fff;
            padding: 2rem;
            text-align: center;
        }
        footer p {
            margin-bottom: 1rem;
        }
        .social-links a {
            margin: 0 1rem;
            font-size: 1.5rem;
        }
        /* Responsive */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2rem;
            }
            nav ul {
                flex-direction: column;
                margin-top: 1rem;
            }
            nav ul li {
                margin-left: 0;
                margin-bottom: 0.5rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Driftfoot</div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="home" class="hero">
        <h1>Step into Style</h1>
        <p>Discover premium shoes crafted for comfort, durability, and timeless elegance. Driftfoot – where every step matters.</p>
        <a href="#products" class="btn">Explore Collection</a>
    </section>
    <section id="products" class="products">
        <h2>Featured Shoes</h2>
        <div class="product-grid">
            <div class="product">
                <svg width="100%" height="200" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
                    <!-- Custom SVG for Sneaker -->
                    <rect x="50" y="120" width="100" height="40" fill="#000"/>
                    <rect x="60" y="100" width="80" height="20" fill="#fff"/>
                    <circle cx="70" cy="140" r="10" fill="#ccc"/>
                    <circle cx="130" cy="140" r="10" fill="#ccc"/>
                    <text x="100" y="180" text-anchor="middle" font-size="12" fill="#000">Drift Sneaker</text>
                </svg>
                <h3>Drift Sneaker - $120</h3>
            </div>
            <div class="product">
            <svg width="100%" height="200" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
                    <!-- Custom SVG for Boot -->
                    <rect x="40" y="100" width="120" height="60" fill="#8B4513"/>
                    <rect x="50" y="80" width="100" height="20" fill="#654321"/>
                    <polygon points="40,160 60,180 140,180 160,160" fill="#000"/>
                    <text x="100" y="190" text-anchor="middle" font-size="12" fill="#000">Urban Boot</text>
                </svg>
                <h3>Urban Boot - $150</h3>
            </div>
            <div class="product">
                <svg width="100%" height="200" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
                    <!-- Custom SVG for Loafer -->
                    <rect x="50" y="130" width="100" height="30" fill="#000"/>
                    <rect x="60" y="110" width="80" height="20" fill="#fff"/>
                    <ellipse cx="100" cy="150" rx="40" ry="10" fill="#ccc"/>
                    <text x="100" y="180" text-anchor="middle" font-size="12" fill="#000">Classic Loafer</text>
                </svg>
                <h3>Classic Loafer - $100</h3>
            </div>
        </div>
    </section>
    <section id="about" class="about">
        <h2>About Driftfoot</h2>
        <p>Founded in 2025, Driftfoot is dedicated to creating high-quality shoes that blend innovation with tradition. Our designs draw inspiration from urban landscapes and natural terrains, ensuring every pair is built for performance and style. We use sustainable materials and ethical manufacturing to make a positive impact on the world.</p>
    </section>
    <footer>
        <p>&copy; 2023 Driftfoot. All rights reserved.</p>
        <div class="social-links">
            <a href="#">Instagram</a>
            <a href="#">Facebook</a>
            <a href="#">Twitter</a>
        </div>
        <p>Contact: info@driftfoot.com | +1 (555) 123-4567</p>
    </footer>
    <script>
        // Smooth scrolling for nav links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>

    
