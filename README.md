
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Glushnev Mikhail Alekseevich">
    <meta name="description" content="MAG Industries – техническая поддержка">
    <meta name="keywords" content="MAG industries, техподдержка, поддержка, Viber, Telegram, помощь">
    <title>MAG Industries | Техническая поддержка</title>
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&family=Roboto:wght@300;400&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --primary: #F3A000;
            --red: #FF0000;
            --bg: #CCE1FE;
            --text: #222;
            --shadow: 0 4px 15px rgba(0,0,0,0.1);
            --card-bg: rgba(255,255,255,0.95);
        }
        
        * { margin: 0; padding: 0; box-sizing: border-box; }
        
        body {
            font-family: 'Roboto', sans-serif;
            background-color: var(--bg);
            color: var(--text);
            line-height: 1.6;
            animation: fadeIn 1.5s ease-out;
        }
        
        .back-btn {
            position: fixed;
            top: 15px;
            left: 15px;
            padding: 10px 18px;
            background: rgba(255,255,255,0.9);
            color: var(--text);
            text-decoration: none;
            font-weight: 600;
            font-size: 0.95rem;
            border-radius: 30px;
            box-shadow: var(--shadow);
            transition: all 0.3s ease;
            z-index: 1000;
            backdrop-filter: blur(10px);
        }
        
        .back-btn:hover {
            background: var(--primary);
            color: white;
            transform: translateY(-3px);
        }
        
        .hero {
            text-align: center;
            padding: 80px 20px 40px;
        }
        
        .logo {
            max-width: 320px;
            border-radius: 20px;
            box-shadow: var(--shadow);
            margin-bottom: 20px;
            transition: transform 0.5s ease;
            animation: slideUp 1s ease-out;
        }
        
        .logo:hover { transform: scale(1.05); }
        
        h1 {
            font-family: 'Montserrat', sans-serif;
            font-size: 3rem;
            color: var(--primary);
            margin: 0 0 10px 0;
        }
        
        .subtitle {
            font-size: 1.6rem;
            color: #333;
            font-weight: 500;
            margin-bottom: 50px;
        }
        
        .support {
            max-width: 900px;
            margin: 0 auto 80px;
            padding: 40px;
            background: var(--card-bg);
            border-radius: 20px;
            box-shadow: var(--shadow);
            text-align: center;
            animation: fadeInUp 1.5s ease-out;
        }
        
        .support h2 {
            font-family: 'Montserrat', sans-serif;
            font-size: 2.6rem;
            color: var(--primary);
            margin-bottom: 30px;
        }
        
        .support p {
            font-size: 1.3rem;
            margin-bottom: 50px;
            color: #444;
            max-width: 700px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .contacts {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
            gap: 60px;
        }
        
        .contact-item {
            text-align: center;
            opacity: 0;
            animation: fadeInUp 1s ease-out forwards;
        }
        
        .contact-item a {
            display: block;
            transition: transform 0.4s ease;
        }
        
        .contact-item a:hover {
            transform: scale(1.2) translateY(-10px);
        }
        
        .contact-item img {
            width: 80px;
            height: 80px;
            border-radius: 20px;
            box-shadow: var(--shadow);
            margin-bottom: 15px;
        }
        
        .contact-item span {
            display: block;
            font-size: 1.2rem;
            font-weight: 600;
            color: var(--text);
        }
        
        .contact-item:nth-child(1) { animation-delay: 0.3s; }
        .contact-item:nth-child(2) { animation-delay: 0.6s; }
        
        footer {
            text-align: center;
            padding: 40px;
            background: var(--card-bg);
            font-size: 0.9rem;
            color: #666;
        }
        
        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
        @keyframes slideUp { from { opacity: 0; transform: translateY(50px); } to { opacity: 1; transform: translateY(0); } }
        @keyframes fadeInUp { from { opacity: 0; transform: translateY(30px); } to { opacity: 1; transform: translateY(0); } }
        
        @media (max-width: 768px) {
            .back-btn { top: 10px; left: 10px; padding: 8px 14px; font-size: 0.9rem; }
            .hero { padding-top: 70px; }
            h1 { font-size: 2.4rem; }
            .subtitle { font-size: 1.4rem; }
            .support { margin: 20px; padding: 30px; }
            .support h2 { font-size: 2.2rem; }
            .support p { font-size: 1.1rem; }
            .contacts { gap: 40px; }
            .contact-item img { width: 70px; height: 70px; }
            .contact-item span { font-size: 1.1rem; }
            .logo { max-width: 280px; }
        } 
    </style>
</head>
<body>

    <a href="https://mag858.github.io/MAG-industries/" class="back-btn">← На главную</a>

    <section class="hero">
        <img src="sait/logo_2.jpeg" alt="Логотип MAG Industries" class="logo">
        <h1>future - right now</h1>
        <div class="subtitle">(будущее - прямо сейчас)</div>
    </section>

    <section class="support">
        <h2>Техническая поддержка</h2>
        <p>Если у вас возникли проблемы с сайтом, вопросы по устройствам или любые другие трудности — пишите нам! Мы оперативно ответим и поможем решить всё.</p>
        
        <div class="contacts">
            <div class="contact-item">
                <a href="https://invite.viber.com/?g2=AQBu89D4H5NvBFMoyNSA2udnFcbfp5Zvj4x8Yh21me232gGDte%2BQtlPhs%2BLS5mnX" target="_blank">
                    <img src="sait/viber.jpg" alt="Viber поддержка">
                    <span>Поддержка в Viber</span>
                </a>
            </div>
            
            <div class="contact-item">
                <a href="https://t.me/mag_ind" target="_blank">
                    <img src="sait/telegram.jpeg" alt="Telegram поддержка">
                    <span>Поддержка в Telegram</span>
                </a>
            </div>
        </div>
    </section>

    <footer>
        обновление 3.1 &emsp; январь 2026 г.
    </footer>

</body>
</html>
