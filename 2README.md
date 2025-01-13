<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Afiliados - Inspirado na Shopee</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }

        /* Barra de Navegação Superior */
        .navbar {
            background-color: #ff5722;
            color: white;
            padding: 10px 20px;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            z-index: 1000;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        .navbar a:hover {
            text-decoration: underline;
        }

        /* Espaço abaixo da navbar */
        .content {
            margin-top: 60px;
            padding: 20px;
        }

        /* Banner */
        .banner {
            margin: 20px 0;
            text-align: center;
        }
        .banner img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }

        /* Grid de Produtos */
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        .product-card {
            background: white;
            border: 1px solid #ddd;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
            padding: 15px;
        }
        .product-card img {
            max-width: 150px;
            height: auto;
            margin-bottom: 10px;
        }
        .product-card h3 {
            font-size: 16px;
            margin: 10px 0;
            color: #333;
        }
        .product-card a {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            background-color: #ff5722;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .product-card a:hover {
            background-color: #e64a19;
        }

        /* Anúncios */
        .ads {
            text-align: center;
            margin: 30px 0;
        }
        .ads-placeholder {
            background: #e0e0e0;
            color: #757575;
            padding: 20px;
            border: 2px dashed #bdbdbd;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <div class="navbar">
        <div>
            <a href="#">Home</a>
            <a href="#">Categorias</a>
            <a href="#">Ofertas</a>
        </div>
        <div>
            <a href="#">Login</a>
            <a href="#">Carrinho</a>
        </div>
    </div>

    <div class="content">
        <!-- Banner Principal -->
        <div class="banner">
            <img src="https://via.placeholder.com/1200x300" alt="Banner Principal">
        </div>

        <!-- Espaço para Anúncios -->
        <div class="ads">
            <div class="ads-placeholder">Espaço para Anúncios - Google AdSense</div>
        </div>

        <!-- Grid de Produtos -->
        <div class="product-grid">
            <!-- Produto Exemplo -->
            <div class="product-card">
                <img src="https://via.placeholder.com/150" alt="Produto 1">
                <h3>Produto 1</h3>
                <p>R$ 49,90</p>
                <a href="https://shopee.com.br" target="_blank">Comprar Agora</a>
            </div>
            <div class="product-card">
                <img src="https://via.placeholder.com/150" alt="Produto 2">
                <h3>Produto 2</h3>
                <p>R$ 79,90</p>
                <a href="https://shopee.com.br" target="_blank">Comprar Agora</a>
            </div>
            <!-- Adicione mais produtos aqui -->
        </div>

        <!-- Outro Espaço para Anúncios -->
        <div class="ads">
            <div class="ads-placeholder">Espaço para Anúncios - Google AdSense</div>
        </div>
    </div>
</body>
</html>
