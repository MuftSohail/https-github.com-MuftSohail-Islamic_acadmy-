<!DOCTYPE html>
<html lang="ur">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>اسلامک اکیڈمی - دینی تعلیمات اور رہنمائی کا مرکز</title>
    <meta name="description" content="اسلامک اکیڈمی دینی تعلیمات اور رہنمائی کے لیے ایک مرکز ہے۔">
    <meta name="keywords" content="اسلامک اکیڈمی, دینی تعلیمات, قرآن, حدیث, فقہ, اسلامی تاریخ">
    <meta name="author" content="مفتی محمد سہیل خان شیرانی">
    <link rel="icon" href="path/to/favicon.ico" type="image/x-icon">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* بنیادی اسٹائلز */
        body {
            font-family: 'Roboto', sans-serif;
            direction: rtl;
            background-color: #f9f9f9;
            color: #333;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #007b5e;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        h1, h2, h3 {
            font-family: 'Roboto', sans-serif;
            font-weight: 700;
            margin: 0;
        }

        a {
            color: #007b5e;
            text-decoration: none;
        }

        a:hover {
            color: #005f47;
            text-decoration: underline;
        }

        /* نیویگیشن بار */
        nav {
            background-color: #333;
            text-align: center;
            padding: 10px;
        }

        nav a {
            color: white;
            padding: 12px 20px;
            text-decoration: none;
            display: inline-block;
        }

        nav a:hover {
            background-color: #555;
            border-radius: 5px;
        }

        /* سیکشنز */
        section {
            margin: 20px 0;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            background-color: white;
        }

        /* فوٹر */
        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 14px;
            position: relative;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.1);
        }

        /* کارڈز */
        .card {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            padding: 20px;
            margin: 20px;
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        /* ہائی لائٹ */
        .highlight {
            background-color: #fffae5;
            font-weight: bold;
            padding: 5px;
            border-radius: 5px;
        }

        /* ریسپانسیو ڈیزائن */
        @media only screen and (max-width: 768px) {
            nav a {
                display: block;
                margin: 5px 0;
            }

            .menu-toggle {
                display: block;
            }

            .nav-menu {
                display: none;
                flex-direction: column;
            }

            .nav-menu.active {
                display: flex;
            }
        }

        /* اینیمیشنز */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        section {
            animation: fadeIn 1s ease-in-out;
        }

        /* ڈارک موڈ */
        @media (prefers-color-scheme: dark) {
            body {
                background-color: #121212;
                color: #e0e0e0;
            }

            header, footer {
                background-color: #1f1f1f;
            }

            nav {
                background-color: #2c2c2c;
            }

            section {
                background-color: #1f1f1f;
                color: #e0e0e0;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>اسلامک اکیڈمی</h1>
    <p>دینی تعلیمات اور رہنمائی کے لیے ایک مرکز</p>
    <p>مفتی محمد سہیل خان شیرانی فاضل وفاق المدارس العربیہ وفاضل جامعہ دارالعلوم کراچی</p>
</header>

<nav>
    <button class="menu-toggle" aria-label="Toggle Menu">&#9776;</button>
    <div class="nav-menu">
        <a href="#home">ہوم</a>
        <a href="#educational-content">تعلیمی مواد</a>
        <a href="#scholars">علماء کی خدمات</a>
        <a href="#fatwas">فتاویٰ</a>
        <a href="#history">اسلامی تاریخ</a>
        <a href="#introduction">میرا تعارف</a>
        <a href="#contact">رابطہ</a>
    </div>
</nav>

<section id="home">
    <h2>ہوم پیج</h2>
    <p>اسلامک اکیڈمی کا مقصد دینی تعلیمات کی اشاعت اور لوگوں کی رہنمائی ہے۔</p>
    <img src="path/to/image.jpg" alt="اسلامک اکیڈمی" style="width:100%; max-width:600px;">
</section>

<section id="educational-content">
    <h2>تعلیمی مواد</h2>
    <div class="card">
        <h3>قرآن و حدیث پر دروس</h3>
        <p>قرآن و حدیث کی تعلیمات پر مشتمل دروس۔</p>
    </div>
    <div class="card">
        <h3>فقہ کے مختلف مسائل</h3>
        <p>فقہ کے اہم مسائل پر تفصیلی مواد۔</p>
    </div>
</section>

<section id="scholars">
    <h2>مفکرین اور علماء کی خدمات</h2>
    <p>مشہور علماء اور مفکرین کے اقوال اور تعلیمی کاموں کا ذکر کیا جائے گا۔</p>
</section>

<section id="fatwas">
    <h2>فتاویٰ</h2>
    <p>دینی مسائل پر فتاویٰ
