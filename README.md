<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Artisan Aura - Handcrafted Creations with a Distinctive Aura">
    <title>Artisan Aura | Handcrafted Creations</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <nav>
            <div class="logo">
                <h1>Artisan Aura</h1>
            </div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#shop">Shop</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
        <div class="hero">
            <h2>Handcrafted Creations with a Distinctive Aura</h2>
            <a href="#shop" class="cta-button">Shop Now</a>
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="about-section">
        <h2>About Artisan Aura</h2>
        <p>At Artisan Aura, we believe in the art of handcrafted creations. Our artisans craft each piece with passion, care, and love, making sure every product carries a unique story.</p>
    </section>

    <!-- Shop Section -->
    <section id="shop" class="shop-section">
        <h2>Explore Our Collections</h2>
        <div class="products">
            <div class="product-card">
                <img src="product1.jpg" alt="Product 1">
                <h3>Handmade Vase</h3>
                <p>$45.00</p>
                <a href="#" class="product-button">View Product</a>
            </div>
            <div class="product-card">
                <img src="product2.jpg" alt="Product 2">
                <h3>Artisan Jewelry</h3>
                <p>$75.00</p>
                <a href="#" class="product-button">View Product</a>
            </div>
            <div class="product-card">
                <img src="product3.jpg" alt="Product 3">
                <h3>Handwoven Blanket</h3>
                <p>$120.00</p>
                <a href="#" class="product-button">View Product</a>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact-section">
        <h2>Contact Us</h2>
        <form action="#" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit" class="submit-button">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Artisan Aura. All Rights Reserved.</p>
        <ul class="social-links">
            <li><a href="#">Instagram</a></li>
            <li><a href="#">Facebook</a></li>
            <li><a href="#">Pinterest</a></li>
        </ul>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
