<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>سعيدة دراجي - الصفحة الشخصية</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #2A73BA;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        header img {
            max-width: 100px;
            border-radius: 50%;
        }
        main {
            padding: 20px;
        }
        .content-section {
            margin-bottom: 40px;
        }
        .content-section h2 {
            color: #52B953;
        }
        .content-section img {
            max-width: 100%;
            height: auto;
        }
        form {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        form div {
            margin-bottom: 15px;
        }
        form label {
            display: block;
            margin-bottom: 5px;
        }
        form input, form textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        form button {
            background-color: #FED628;
            color: #000;
            border: none;
            padding: 10px 20px;
            border-radius: 4px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #e5c200;
        }
    </style>
</head>
<body>
    <header>
        <img src="your-logo-url-here" alt="Logo">
        <h1>سعيدة دراجي</h1>
        <p>أستاذة لغة عربية</p>
    </header>
    <main>
        <section class="content-section">
            <h2>عن الكتاب</h2>
            <img src="your-book-cover-url-here" alt="واجهة الكتاب">
        </section>
        <section class="content-section">
            <h2>نموذج الاستبيان</h2>
            <form action="your-form-handler-url-here" method="post">
                <div>
                    <label for="name">الاسم الكامل:</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div>
                    <label for="email">البريد الإلكتروني:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div>
                    <label for="message">رسالتك:</label>
                    <textarea id="message" name="message" rows="4" required></textarea>
                </div>
                <button type="submit">إرسال</button>
            </form>
        </section>
    </main>
</body>
</html>
