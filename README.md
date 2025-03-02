<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tech Store - Laptops, Computers & Printers</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 20px auto;
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .product {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            width: 30%;
            text-align: center;
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .product h3 {
            margin: 10px 0;
        }
        .product button {
            background: #28a745;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            border-radius: 5px;
        }
        .product button:hover {
            background: #218838;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Tech Store</h1>
    </header>
    <div class="container">
        <div class="product">
            <img src="laptop.jpg" alt="Laptop">
            <h3>High-Performance Laptop</h3>
            <p>$799.99</p>
            <button>Buy Now</button>
        </div>
        <div class="product">
            <img src="desktop.jpg" alt="Desktop Computer">
            <h3>Powerful Desktop PC</h3>
            <p>$999.99</p>
            <button>Buy Now</button>
        </div>
        <div class="product">
            <img src="printer.jpg" alt="Printer">
            <h3>All-in-One Printer</h3>
            <p>$199.99</p>
            <button>Buy Now</button>
        </div>
    </div>
    <footer>
        <p>&copy; 2025 Tech Store. All Rights Reserved.</p>
    </footer>
</body>
</html>
