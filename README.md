<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Art Rose | Continent Seller</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9; /* Bright, colorful background */
            color: #333;
        }
        header {
            background-color: #ffc107; /* Bright yellow header */
            padding: 20px;
            text-align: center;
        }
        h1, h2 {
            margin: 0;
        }
        nav {
            background-color: #fff;
            text-align: center;
            padding: 10px;
        }
        nav a {
            text-decoration: none;
            color: #333;
            margin: 0 10px;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: auto;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Art Rose's Continent Emporium</h1>
        <p>Your one-stop shop for unique continents!</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about" class="container">
        <h2>About Art Rose</h2>
        <p>Welcome to my website! I'm Art Rose, and I have a passion for discovering and sharing unique continents with the world. Each continent in my collection has its own story and beauty waiting to be explored.</p>
    </section>
    <section id="products" class="container">
        <h2>Our Products</h2>
        <p>Explore our selection of breathtaking continents available for sale:</p>
        <!-- Insert your continent products here -->
        <div>
            <h3>Continent Name</h3>
            <p>Description: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut hendrerit, libero a tristique tincidunt, ante elit ultricies arcu.</p>
            <p>Price: $XXX</p>
            <button>Add to Cart</button>
        </div>
    </section>
    <section id="contact" class="container">
        <h2>Contact Us</h2>
        <p>Have a question or want to learn more about our continents? Feel free to reach out!</p>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br><br>
            <button type="submit">Send Message</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Art Rose - Continent Emporium</p>
    </footer>
</body>
</html>
