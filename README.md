<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>SuperNova | Modern Women's Fashion</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #ff6ec4, #7873f5);
            color: white;
        }

        header {
            padding: 20px 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            font-size: 32px;
            letter-spacing: 2px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-weight: bold;
            transition: 0.3s;
        }

        nav a:hover {
            color: #ffe600;
        }

        .hero {
            text-align: center;
            padding: 100px 20px;
        }

        .hero h2 {
            font-size: 48px;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 20px;
            margin-bottom: 30px;
        }

        .btn {
            padding: 12px 30px;
            background: #ffe600;
            color: black;
            font-weight: bold;
            border: none;
            border-radius: 30px;
            cursor: pointer;
            transition: 0.3s;
        }

        .btn:hover {
            background: white;
            transform: scale(1.1);
        }

        .products {
            background: white;
            color: black;
            padding: 60px 20px;
            text-align: center;
        }

        .products h2 {
            margin-bottom: 40px;
            font-size: 36px;
            color: #ff3cac;
        }

        .product-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
        }

        .product {
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            padding: 20px;
            border-radius: 20px;
            width: 250px;
            transition: 0.3s;
        }

        .product:hover {
            transform: translateY(-10px);
        }

        .product img {
            width: 100%;
            border-radius: 15px;
            margin-bottom: 15px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: #111;
            font-size: 14px;
        }

        @media(max-width: 768px) {
            .hero h2 {
                font-size: 32px;
            }
            .product-container {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>SuperNova ✨</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">Shop</a>
        <a href="#">New Arrivals</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Shine Like A SuperNova</h2>
    <p>Modern, Bold & Beautiful Women's Fashion</p>
    <button class="btn">Shop Now</button>
</section>

<section class="products">
    <h2>Trending Collection</h2>

    <div class="product-container">

        <div class="product">
            <img src="https://via.placeholder.com/250x300" alt="Dress">
            <h3>Elegant Summer Dress</h3>
            <p>$49.99</p>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/250x300" alt="Top">
            <h3>Chic Crop Top</h3>
            <p>$29.99</p>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/250x300" alt="Jacket">
            <h3>Stylish Jacket</h3>
            <p>$79.99</p>
        </div>

    </div>
</section>

<footer>
    © 2026 SuperNova | Designed with ✨ for Modern Women
</footer>

</body>
</html>
