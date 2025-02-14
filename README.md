<html lang="en">
  <style>
    body {
            font-family: sans-serif;
            background-color: #FFB6C1;
        }
.container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        .header {
            text-align: center;
            margin-bottom: 20px;
        }
        .movie-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            grid-gap: 20px;
        }
        .movie {
            border: 1px solid #ccc;
            padding: 10px;
            text-align: center;
        }
        .movie img {
            max-width: 100%;
            height: auto;
            margin-bottom: 10px;
        }
        .footer {
            text-align: center;
            margin-top: 20px;
        }
  </style>
<head>
    <title>Сайт про фільми</title>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Сайт про фільми</h1>
        </div>
        <div class="movie-grid">
            <div class="movie">
                <img src="https://upload.wikimedia.org/wikipedia/uk/6/69/%D0%A2%D0%BE%D1%80_3._%D0%A0%D0%B0%D2%91%D0%BD%D0%B0%D1%80%D0%BE%D0%BA_%28%D0%BF%D0%BB%D0%B0%D0%BA%D0%B0%D1%82_%D1%84%D1%96%D0%BB%D1%8C%D0%BC%D1%83%29.jpg">
                <h3>Тор рагнарок</h3>
            </div>
            <div class="movie">
                <img src="https://upload.wikimedia.org/wikipedia/uk/e/e3/Infinity_War_Poster.jpg">
                <h3>Месники:Війна нескінченості</h3>
            </div>
            <div class="movie">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTQb_0Bh1sbteAtSM4Sg5P_yLc__ib6B6G7AQ&s">
                <h3>Месники</h3>
            </div>
        </div>
        <div class="footer">
            <p>&copy; 2023 Моя компанія. Усі права захищено.</p>
        </div>
    </div>
</body>
</html>
