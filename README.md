Sureler
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@700&display=swap" rel="stylesheet">
    <title>Дизайн Сүрелер с красивым оформлением</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: url('https://images.unsplash.com/photo-1506748686214-e9df14d4d9d0') no-repeat center center fixed;
            background-size: cover;
            color: #333;
        }
        .container {
            padding: 20px;
            max-width: 900px;
            margin: auto;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }
        h2 {
            font-family: 'Roboto', sans-serif;
            font-weight: 700;
            color: #388E3C;
            text-align: center;
            font-size: 3em; /* Увеличенный размер шрифта */
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3); /* Тень для эффекта */
        }
        .card {
            background: #ffffff;
            border-radius: 10px;
            margin: 15px 0;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
            display: flex;
            align-items: center;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }
        .card img {
            border-radius: 10px;
            width: 100px;
            height: auto;
            margin-right: 15px;
        }
        .button {
            display: inline-block;
            padding: 10px 15px;
            margin-top: 10px;
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: #388E3C;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Сүрелер</h2>
        <div class="card">
            <img src="https://via.placeholder.com/100" alt="Сура Аль-Фатиха">
            <div>
                <h3>Сура Аль-Фатиха</h3>
                <p>Сура открытия, содержащая основные принципы веры.</p>
                <a href="#" class="button">Читать больше</a>
            </div>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/100" alt="Сура Аль-Бакара">
            <div>
                <h3>Сура Аль-Бакара</h3>
                <p>Самая длинная сура Корана, охватывающая множество тем.</p>
                <a href="#" class="button">Читать больше</a>
            </div>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/100" alt="Сура Аль-Имран">
            <div>
                <h3>Сура Аль-Имран</h3>
                <p>Сура, посвященная вопросам веры и единства.</p>
                <a href="#" class="button">Читать больше</a>
            </div>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/100" alt="Сура Ан-Ниса">
            <div>
                <h3>Сура Ан-Ниса</h3>
                <p>Сура о правах женщин и социальной справедливости.</p>
                <a href="#" class="button">Читать больше</a>
            </div>
        </div>
    </div>
</body>
</html>
