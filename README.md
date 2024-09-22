<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meus Produtos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        section {
            margin: 20px auto;
            max-width: 800px;
        }
        h1 {
            text-align: center;
        }
        .product-list {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .product-item {
            background-color: white;
            border: 1px solid #ddd;
            padding: 15px;
            width: 200px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .product-item a {
            text-decoration: none;
            color: #4CAF50;
            font-weight: bold;
        }
    </style>
</head>
<body>

<header>
    <h1>Meus Produtos</h1>
</header>

<section>
    <div class="product-list">
        <div class="product-item">
            <h2>Produto 1</h2>
            <p>Descrição do Produto 1.</p>
            <a href="https://linkproduto1.com" target="_blank">Ver Produto</a>
        </div>
        <div class="product-item">
            <h2>Produto 2</h2>
            <p>Descrição do Produto 2.</p>
            <a href="https://linkproduto2.com" target="_blank">Ver Produto</a>
        </div>
        <div class="product-item">
            <h2>Produto 3</h2>
            <p>Descrição do
