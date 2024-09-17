# My-website
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Обо мне</title>
    <style>
        /* Общие стили */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f4f8;
            color: #333;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }
        header {
            background-color: #4a90e2;
            color: white;
            text-align: center;
            padding: 2rem 0;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        header h1 {
            font-size: 2.8rem;
            margin: 0;
            font-weight: bold;
        }
        section {
            max-width: 1000px;
            margin: 2rem auto;
            padding: 2rem;
            background-color: white;
            border-radius: 12px;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
        }
        h2 {
            font-size: 2.2rem;
            color: #4a90e2;
            margin-bottom: 1rem;
        }
        p {
            font-size: 1.2rem;
            line-height: 1.8;
            margin-bottom: 1.5rem;
        }
        .contact-info h3 {
            font-size: 1.5rem;
            color: #333;
            margin-bottom: 1rem;
        }
        .contact-info p {
            margin: 0.3rem 0;
        }
        /* Анимация наводки на кнопки */
        a.contact-button {
            display: inline-block;
            padding: 0.75rem 1.5rem;
            font-size: 1.1rem;
            color: white;
            background-color: #4a90e2;
            text-decoration: none;
            border-radius: 6px;
            transition: background-color 0.3s;
        }
        a.contact-button:hover {
            background-color: #357ABD;
        }
        footer {
            background-color: #4a90e2;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: auto;
        }
        footer p {
            margin: 0;
            font-size: 1rem;
        }
        /* Адаптивный дизайн */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }
            section {
                margin: 1rem;
                padding: 1.5rem;
            }
            h2 {
                font-size: 1.8rem;
            }
            p {
                font-size: 1.1rem;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Привет! Я [Тохир]</h1>
    </header>

    <section>
        <h2>Обо мне</h2>
        <p>Я увлечён [разными предметами и сильно интересуюсь английским ]. 
        Мне нравится заниматься [математика, программирование].</p>

        <div class="contact-info">
            <h3>Узбекистан,Фергана</h3>
            <p>Email: <a href="mailto:[tolibjonov1311@gmail.com]" class="contact-button">Связаться по почте</a></p>
            <p>Телефон: [+998916760905]</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 [Твоё имя]. Все права защищены.</p>
    </footer>

</body>
</html>
