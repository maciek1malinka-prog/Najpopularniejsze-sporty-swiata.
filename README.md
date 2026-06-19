Śr, 10:52
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Najpopularniejsze Sporty Świata</title>

    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:'Poppins', sans-serif;
        }

        body{
            background:#f5f7fa;
            color:#333;
        }

        header{
            background:#111827;
            color:white;
            padding:20px 8%;
            display:flex;
            justify-content:space-between;
            align-items:center;
        }

        .logo{
            font-size:1.6rem;
            font-weight:700;
        }

        nav ul{
            list-style:none;
            display:flex;
            gap:25px;
        }

        nav a{
            color:white;
            text-decoration:none;
            transition:.3s;
        }

        nav a:hover{
            color:#38bdf8;
        }

        .hero{
            height:85vh;
            display:flex;
            justify-content:center;
            align-items:center;
            text-align:center;
            background:linear-gradient(rgba(0,0,0,.6), rgba(0,0,0,.6)),
            url('https://images.unsplash.com/photo-1517649763962-0c623066013b');
            background-size:cover;
            background-position:center;
            color:white;
            padding:20px;
        }

        .hero-content h1{
            font-size:4rem;
            margin-bottom:20px;
        }

        .hero-content p{
            font-size:1.2rem;
            max-width:700px;
            margin:auto;
            margin-bottom:30px;
        }

        .btn{
            display:inline-block;
            padding:15px 35px;
            background:#38bdf8;
            color:white;
            text-decoration:none;
            border-radius:50px;
            transition:.3s;
        }

        .btn:hover{
            background:#0ea5e9;
        }

        section{
            padding:80px 8%;
        }

        .section-title{
            text-align:center;
            margin-bottom:50px;
        }

        .section-title h2{
            font-size:2.5rem;
            color:#111827;
        }

        .sports-grid{
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
            gap:25px;
        }

        .card{
            background:white;
            border-radius:15px;
            overflow:hidden;
            box-shadow:0 5px 15px rgba(0,0,0,.1);
            transition:.3s;
        }

        .card:hover{
            transform:translateY(-10px);
        }

        .card img{
            width:100%;
            height:200px;
            object-fit:cover;
        }

        .card-content{
            padding:20px;
        }

        .card-content h3{
            margin-bottom:10px;
        }

        .stats{
            background:#111827;
            color:white;
        }

        .stats-container{
            display:grid;
            grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
            gap:30px;
            text-align:center;
        }

        .stat h3{
            font-size:3rem;
            color:#38bdf8;
        }

        footer{
            background:#0f172a;
            color:white;
            text-align:center;
            padding:30px;
        }
    </style>
</head>
<body>

<header>
    <div class="logo">🌍 World Sports</div>

    <nav>
        <ul>
            <li><a href="#">Strona Główna</a></li>
            <li><a href="#">Sporty</a></li>
            <li><a href="#">Ranking</a></li>
            <li><a href="#">Kontakt</a></li>
        </ul>
    </nav>
</header>

<section class="hero">
    <div class="hero-content">
        <h1>Najpopularniejsze Sporty Świata</h1>
        <p>
            Poznaj dyscypliny sportowe, które przyciągają miliardy kibiców
            na całym świecie.
        </p>

        <a href="#sports" class="btn">Zobacz Ranking</a>
    </div>
</section>

<section id="sports">
    <div class="section-title">
        <h2>Top Sporty</h2>
    </div>

    <div class="sports-grid">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1574629810360-7efbbe195018" alt="Piłka nożna">
            <div class="card-content">
                <h3>⚽ Piłka Nożna</h3>
                <p>Najpopularniejszy sport świata z miliardami fanów.</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1546519638-68e109498ffc" alt="Koszykówka">
            <div class="card-content">
                <h3>🏀 Koszykówka</h3>
                <p>Sport globalny rozwijany przez NBA i ligi krajowe.</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1531415074968-036ba1b575da" alt="Tenis">
            <div class="card-content">
                <h3>🎾 Tenis</h3>
                <p>Jedna z najbardziej prestiżowych dyscyplin świata.</p>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1560272564-c83b66b1ad12" alt="Krykiet">
            <div class="card-content">
                <h3>🏏 Krykiet</h3>
                <p>Ogromnie popularny szczególnie w Azji Południowej.</p>
            </div>
        </div>

    </div>
</section>

<section class="stats">
    <div class="section-title">
        <h2>Sport w Liczbach</h2>
    </div>

    <div class="stats-container">

        <div class="stat">
            <h3>4B+</h3>
            <p>Fanów piłki nożnej</p>
        </div>

        <div class="stat">
            <h3>200+</h3>
            <p>Krajów uczestniczących w igrzyskach</p>
        </div>

        <div class="stat">
            <h3>3B+</h3>
            <p>Kibiców krykieta</p>
        </div>

        <div class="stat">
            <h3>450M+</h3>
            <p>Fanów koszykówki</p>
        </div>

    </div>
</section>

<footer>
    <p>&copy; 2026 World Sports | Wszystkie prawa zastrzeżone.</p>
</footer>

</body>
</html>
