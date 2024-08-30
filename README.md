<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ваш Бизнес - Гламурная Обувь</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff;
            color: #333;
        }
        header {
            background-color: #ff69b4;
            color: #fff;
            text-align: center;
            padding: 2rem;
        }
        header h1 {
            font-size: 2.5rem;
            margin: 0;
            font-family: 'Brush Script MT', cursive;
        }
        main {
            padding: 2rem;
        }
        .description {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            text-align: center;
        }
        .products {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .product {
            background-color: #f8f8f8;
            padding: 1rem;
            margin: 1rem;
            width: 200px;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .product img {
            max-width: 100%;
            border-radius: 10px;
        }
        .product h2 {
            font-size: 1.5rem;
            color: #ff69b4;
            font-family: 'Brush Script MT', cursive;
        }
        footer {
            background-color: #ff69b4;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Гламурная Обувь</h1>
</header>

<main>
    <div class="description">
        Добро пожаловать в наш магазин! Здесь вы найдете самую стильную и гламурную обувь для женщин.
    </div>

    <div class="products">
        <div class="product">
            <img src="shoe1.jpg" alt="Гламурные туфли 1">
            <h2>Туфли Золушки</h2>
            <p>Изящные туфли с блестками для особенных случаев.</p>
        </div>
        <div class="product">
            <img src="shoe2.jpg" alt="Гламурные туфли 2">
            <h2>Шпильки</h2>
            <p>Элегантные шпильки для вечерних выходов.</p>
        </div>
        <div class="product">
            <img src="shoe3.jpg" alt="Гламурные туфли 3">
            <h2>Ботильоны</h2>
            <p>Комфорт и стиль в каждой детали.</p>
        </div>
    </div>
</main>

<footer>
    Адрес магазина: ул. Примерная, 123, г. Москва
</footer>

</body>
</html>
