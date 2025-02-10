
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Послание</title>
    <style>
        body {
            background-color: #ffe6e6;
            font-family: 'Arial', sans-serif;
            text-align: center;
            color: #ff4d4d;
            position: relative;
            overflow: hidden;
            margin: 0;
            padding: 0;
            height: 100vh;
        }
        h1 {
            font-size: 3em;
            margin-top: 50px;
            position: relative;
            z-index: 2;
            animation: fadeIn 2s ease-in-out, floatText 3s infinite ease-in-out;
        }
        p {
            font-size: 2em;
            margin: 20px 0;
            position: relative;
            z-index: 2;
            animation: fadeIn 3s ease-in-out, floatText 4s infinite ease-in-out;
        }
        .photos {
            display: flex;
            justify-content: center;
            margin-top: 30px;
            position: relative;
            z-index: 2;
            animation: fadeIn 4s ease-in-out;
        }
        .photos img {
            width: 200px;
            height: auto;
            margin: 10px;
            border-radius: 10px;
            border: 2px solid #ff4d4d;
        }
        .heart {
            color: #ff4d4d;
            font-size: 2em;
            position: absolute;
            z-index: 1;
            animation: float 5s infinite ease-in-out, rotate 4s infinite linear;
        }
        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }
        @keyframes rotate {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
        @keyframes floatText {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-10px); }
        }
    </style>
</head>
<body>
    <h1>Я люблю тебя, милая!</h1>
    <p>Ты самая лучшая на свете!</p>
    
    <div class="photos">
        <img src="1.jpg" alt="Фото 1">
        <img src="2.jpg" alt="Фото 2">
        <img src="3.jpg" alt="Фото 3">
    </div>

    <!-- Сердечки, разбросанные по странице -->
    <div class="heart" style="top: 10%; left: 5%;">&#10084;</div>
    <div class="heart" style="top: 20%; left: 80%;">&#10084;</div>
    <div class="heart" style="top: 40%; left: 15%;">&#10084;</div>
    <div class="heart" style="top: 60%; left: 70%;">&#10084;</div>
    <div class="heart" style="top: 80%; left: 10%;">&#10084;</div>
    <div class="heart" style="top: 30%; left: 50%;">&#10084;</div>
    <div class="heart" style="top: 50%; left: 90%;">&#10084;</div>
    <div class="heart" style="top: 70%; left: 30%;">&#10084;</div>
    <div class="heart" style="top: 90%; left: 60%;">&#10084;</div>
    <div class="heart" style="top: 10%; left: 40%;">&#10084;</div>
</body>
</html>
