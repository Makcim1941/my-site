<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <title>Уклідовa Компанія "БудМайстер"</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: #f0f0f0;
        }
        header {
            background: #003366;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            text-align: center;
            background: #0055aa;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 900px;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .hero img {
            width: 100%;
            border-radius: 10px;
        }
        h2 {
            color: #003366;
        }
        .btn {
            display: inline-block;
            background: #007bff;
            color: white;
            padding: 12px 20px;
            border-radius: 5px;
            text-decoration: none;
            font-size: 18px;
            margin-top: 10px;
        }
        .btn:hover {
            background: #0056b3;
        }
        footer {
            background: #003366;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
    </style>
</head>
<body>

<header>
    <h1>Уклідовa Компанія "БудМайстер"</h1>
    <p>Будуємо якісно. Надійно. Професійно.</p>
</header>

<nav>
    <a href="#">Головна</a>
    <a href="#services">Послуги</a>
    <a href="#contacts">Контакти</a>
</nav>

<div class="container">
    <div class="hero">
        <img src="https://images.unsplash.com/photo-1591012911207-0db6f625f9c9?auto=format&fit=crop&w=1200&q=80" alt="Будівництво">
    </div>

    <h2 id="about">Про нас</h2>
    <p>
        Уклідовa компанія <b>"БудМайстер"</b> — це команда професіоналів з багаторічним досвідом у сфері будівництва.  
        Ми займаємося зведенням житлових будинків, ремонтом квартир, фасадними роботами та благоустроєм територій.
    </p>

    <h2 id="services">Наші послуги</h2>
    <ul>
        <li>Будівництво приватних будинків</li>
        <li>Капітальний та косметичний ремонт</li>
        <li>Утеплення та фасадні роботи</li>
        <li>Демонтаж та підготовчі роботи</li>
        <li>Ландшафтний дизайн та благоустрій</li>
    </ul>

    <img src="https://images.unsplash.com/photo-1581092337420-1c01f1f5c3fa?auto=format&fit=crop&w=1200&q=80" 
         style="width:100%; border-radius:10px; margin-top:15px;">

    <a class="btn" href="#contacts">Зв’язатися з нами</a>

    <h2 id="contacts" style="margin-top: 40px;">Контактна інформація</h2>
    <p><b>Адреса:</b> м. Київ, вул. Будівельників, 12</p>
    <p><b>Телефон:</b> +380 67 123 45 67</p>
    <p><b>Email:</b> budmaster@example.com</p>

    <img src="https://images.unsplash.com/photo-1581092795360-f2f8ec99b05d?auto=format&fit=crop&w=1200&q=80"
         style="width:100%; border-radius:10px; margin-top:15px;">
</div>

<footer>
    © 2025 БудМайстер. Всі права захищені.
</footer>

</body>
</html>
