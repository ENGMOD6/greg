<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>موقع بسيط مع نموذج</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 20px;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 20px;
        }
        .contact-form {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
            box-sizing: border-box;
        }
        .contact-form button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #45a049;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: absolute;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>مرحبا بك في الموقع البسيط</h1>
</header>

<nav>
    <a href="#">الرئيسية</a>
    <a href="#">عن الموقع</a>
    <a href="#">اتصل بنا</a>
</nav>

<div class="container">
    <h2>نموذج التواصل</h2>
    <p>إذا كان لديك أي استفسار أو ملاحظة، يمكنك إرسالها من خلال النموذج التالي:</p>

    <div class="contact-form">
        <form action="#" method="POST">
            <label for="name">الاسم الكامل:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">البريد الإلكتروني:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">رسالتك:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">إرسال</button>
        </form>
    </div>
</div>

<footer>
    <p>جميع الحقوق محفوظة &copy; 2025</p>
</footer>

</body>
</html>
