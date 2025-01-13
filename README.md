<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site de Afiliados - Shopee</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #ff4500;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .product {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px;
            border-bottom: 1px solid #ddd;
        }
        .product:last-child {
            border-bottom: none;
        }
        .product img {
            max-width: 100px;
            border-radius: 5px;
        }
        .product-info {
            flex: 1;
            margin-left: 20px;
        }
        .product-title {
            font-size: 18px;
            font-weight: bold;
            margin: 0 0 10px;
        }
        .product-link {
            text-decoration: none;
            color: white;
            background-color: #ff4500;
            padding: 10px 15px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .product-link:hover {
            background-color: #e03e00;
        }
    </style>
</head>
<body>
    <header>
        <h1>Site de Afiliados - Shopee</h1>
        <p>Confira nossas recomendações e aproveite as ofertas!</p>
    </header>
    <div class="container">
        <div class="product">
            <img src="https://via.placeholder.com/100" alt="Produto 1">
            <div class="product-info">
                <h2 class="product-title">Produto 1</h2>
                <p>Descrição breve do produto 1. Aproveite essa oferta incrível!</p>
            </div>
            <a class="product-link" href="https://shopee.com.br/link-afiliado-produto1" target="_blank">Comprar agora</a>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/100" alt="Produto 2">
            <div class="product-info">
                <h2 class="product-title">Produto 2</h2>
                <p>Descrição breve do produto 2. Não perca essa oportunidade!</p>
            </div>
            <a class="product-link" href="https://shopee.com.br/link-afiliado-produto2" target="_blank">Comprar agora</a>
        </div>
        <!-- Adicione mais produtos aqui -->
    </div>
</body>
</html>
