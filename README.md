<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой сайт с товарами</title>
    <style>
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .product {
            display: flex;
            margin-bottom: 20px;
        }

        .product img {
            max-width: 200px; /* Задайте ширину изображения по вашему усмотрению */
            height: auto;
        }

        .description {
            margin-left: 20px; /* Расстояние между изображением и описанием */
        }

        /* Медиа-запрос для адаптивного дизайна */
        @media screen and (min-width: 768px) {
            .product {
                flex-direction: row;
                align-items: center;
            }
            .description {
                margin-left: 50px; /* Увеличьте расстояние на больших экранах */
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="product">
            <img src="https://github.com/CHex0K/Resume/blob/main/ЦП1.png" alt="Название товара">
            <div class="description">
                <h2>Название товара</h2>
                <p>Описание товара здесь...</p>
            </div>
        </div>
        <!-- Повторяем блок для других товаров -->
        <div class="product">
            <img src="https://github.com/CHex0K/Resume/blob/main/ЦП1.png" alt="Название другого товара">
            <div class="description">
                <h2>Название другого товара</h2>
                <p>Описание другого товара здесь...</p>
            </div>
        </div>
        <!-- Можете добавить больше блоков товаров -->
    </div>
</body>
</html>
