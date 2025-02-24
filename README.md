<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Простая Веб-Страница</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }

        header {
            background-color: #3498db;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        header h1 {
            margin: 0;
        }

        nav {
            background-color: #2980b9;
            padding: 10px 0;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            display: inline-block;
        }

        main {
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #3498db;
        }

        p {
            line-height: 1.6;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position:relative;
            bottom:0;
            width:100%;
        }

        .highlight {
            background-color: yellow;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <header>
        <h1>Добро пожаловать на мою страницу!</h1>
    </header>

    <nav>
        <a href="#">Главная</a>
        <a href="#">Обо мне</a>
        <a href="#">Услуги</a>
        <a href="#">Контакты</a>
    </nav>

    <main>
        <h2>Привет!</h2>
        <p>Это простая веб-страница, созданная с использованием чистого HTML и CSS.  Здесь вы найдете полезную информацию о <span class="highlight">наших услугах</span> и как с нами связаться.</p>

        <h2>Наши услуги</h2>
        <p>Мы предлагаем широкий спектр услуг, включая: </p>
        <ul>
            <li>Разработка веб-сайтов</li>
            <li>SEO-оптимизация</li>
            <li>Поддержка веб-сайтов</li>
        </ul>

        <h2>Контакты</h2>
        <p>Вы можете связаться с нами по электронной почте: <a href="mailto:info@example.com">info@example.com</a> или по телефону: +7 (123) 456-78-90.</p>
    </main>

    <footer>
        &copy; 2023 Моя веб-страница
    </footer>

</body>
</html>
