
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Grocery Central</title>
    <style>
        /* Basic CSS for layout */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #f8f8f8;
            padding: 10px 20px;
            text-align: center;
        }
        .nav-items {
            display: flex;
            justify-content: center;
            background-color: #eee;
            padding: 10px;
        }
        .nav-items a {
            padding: 8px 16px;
            text-decoration: none;
            color: #333;
        }
        .intro {
            background-color: #fff;
            padding: 20px;
            text-align: center;
        }
        .categories {
            display: flex;
            justify-content: space-around;
            padding: 20px;
        }
        .category {
            text-align: center;
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
    </style>
</head>
<body>
    <header class="header">
        <h1> EazyShop</h1>
    </header>
    <nav class="nav-items">
                <a href="sign in.html">Sign In</a>
        <a href="signup.html">Sign up</a>
<a href="cart.html">cart</a>
<a href="checkout.html">checkout</a>

    </nav>
    <main>
        <section class="intro">
            <h2>Welcome to  EazyShop!</h2>
            <p>Your one-stop shop for all your needs.</p>
        </section>
        <section class="categories">
            <div class="category">
                <a href="fruits.html">
                    <h3>Fruits</h3>
                    <img src="fruitimage.jpeg" alt="Fruits" width="200">
                </a>
            </div>
            <div class="category">
                <a href="vegetables.html">
                    <h3>Vegetables</h3>
                    <img src="vegetables.jpeg" alt="Vegetables" width="200">
                </a>
            </div>
            <div class="category">
                <a href="clothes.html">
                    <h3>Clothes</h3>
                    <img src="clothes.jpeg" alt="Clothes" width="300">
                </a>
            </div>
            <div class="category">
                <a href="electronics.html">
                    <h3>Electronics</h3>
                    <img src="electrictools.jpeg" alt="Electronics" width="400">
                </a>
            </div>
        </section>
    </main>
    <footer class="footer">
        <p>&copy; 2024 Grocery Central</p>
    </footer>
</body>
</html>
