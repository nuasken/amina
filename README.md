<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Пригласительное на День Рождения Амины</title>
    <style>
        /* Оформление страницы */
        body {
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: 'Comic Sans MS', sans-serif;
            background-color: #ffe6f2;
            color: #333;
            height: 100vh;
            margin: 0;
            background-image: url('https://i.imgur.com/FpLxPyQ.png'); /* фон с узором */
            background-size: cover;
        }

        /* Оформление контейнера приглашения */
        .invite-container {
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 15px;
            padding: 20px;
            text-align: center;
            width: 90%;
            max-width: 400px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            position: relative;
        }

        /* Заголовок */
        h1 {
            font-size: 26px;
            color: #ff85b2;
            margin-top: 0;
            margin-bottom: 5px;
        }

        /* Основной текст */
        p {
            margin: 10px 0;
            font-size: 18px;
            color: #666;
        }

        /* Специальные стили для времени и места */
        .date, .location, .time {
            font-weight: bold;
            color: #ff85b2;
        }

        /* Картинки */
        .flower {
            width: 60px;
            position: absolute;
        }

        .flower-top-left {
            top: -30px;
            left: -30px;
        }

        .flower-bottom-right {
            bottom: -30px;
            right: -30px;
        }
    </style>
</head>
<body>
    <div class="invite-container">
        <!-- Верхний цветок -->
        <img src="https://i.imgur.com/sOIThsO.png" alt="Цветок" class="flower flower-top-left">

        <h1>Ты приглашен на День Рождения!</h1>
        <p>Приглашаем тебя отметить день рождения</p>
        <p class="date">Амины</p>
        <p>Встречаемся в:</p>
        <p class="location">Кафе "Рай-Сай"</p>
        <p>Начало:</p>
        <p class="time">14:00</p>

        <!-- Нижний цветок -->
        <img src="https://i.imgur.com/sOIThsO.png" alt="Цветок" class="flower flower-bottom-right">
    </div>
</body>
</html>
