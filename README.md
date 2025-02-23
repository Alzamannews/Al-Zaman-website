# Al-Zaman-website
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>يوسف - الزمن الإخبارية</title>
    <style>
        body {<script src="script.js"></script>
            font-family: Arial, sans-serif;
            direction: rtl;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
           
        }
        header {<link rel="stylesheet" href="styles.css">
            background-color: #2c3e50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            text-align: center;
            background-color: #34495e;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 15px;
            font-size: 16px;
        }
        nav a:hover {
            background-color: #2980b9;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }
        h1, h2 {
            color: #2c3e50;
        }
        .news-section, .contact-form {
            margin-bottom: 40px;
        }
        .news-article {
            background-color: white;
            margin-bottom: 20px;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        .contact-form button {
            background-color: #2980b9;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
        }
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>يوسف - الزمن الإخبارية</h1>
</header>

<nav>
    <a href="#">الرئيسية</a>
    <a href="#">الأخبار</a>
    <a href="#">التواصل</a>
    <a href="#">عن الموقع</a>
</nav>

<div class="container">

    <div class="news-section">
        <h2>آخر الأخبار</h2>
        <div class="news-article">
            <h3>عنوان الخبر الأول</h3>
            <p>محتوى الخبر الأول. هنا يمكن كتابة تفاصيل الخبر أو المقال.</p>
        </div>
        <div class="news-article">
            <h3>عنوان الخبر الثاني</h3>
            <p>محتوى الخبر الثاني. يمكن إضافة تفاصيل إضافية حول الخبر أو المقال.</p>
        </div>
    </div>

    <div class="contact-form">
        <h2>تواصل معنا</h2>
        <form action="#" method="post">
            <input type="text" name="name" placeholder="اسمك" required>
            <input type="email" name="email" placeholder="بريدك الإلكتروني" required>
            <textarea name="message" placeholder="رسالتك" required></textarea>
            <button type="submit">إرسال</button>
        </form>
    </div>

</div>

<footer>
    <p>&copy; 2025 يوسف - الزمن الإخبارية</p>
</footer>

</body>
</html>
