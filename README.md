# MiccadeMilena

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Loja</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 10px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .product {
            background: #fff;
            padding: 20px;
            margin: 20px 0;
            border: 1px solid #ddd;
        }
        .product img {
            max-width: 100%;
        }
        .product h2 {
            margin: 0 0 10px;
        }
        .product p {
            color: #555;
        }
        .product .price {
            color: #b12704;
            font-size: 1.2em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Minha Loja</h1>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Produtos</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>
    <div class="container">
        <div class="product">
            <img src="produto1.jpg" alt="Produto 1">
            <h2>Produto 1</h2>
            <p>Descrição do produto 1.</p>
            <p class="price">R$ 100,00</p>
        </div>
        <div class="product">
            <img src="produto2.jpg" alt="Produto 2">
            <h2>Produto 2</h2>
            <p>Descrição do produto 2.</p>
            <p class="price">R$ 150,00</p>
        </div>
    </div>
</body>
</html>