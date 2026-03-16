<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Pekin Tovar</title>
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <style>
        body { font-family: sans-serif; text-align: center; background-color: #f4f4f4; }
        h1 { color: #0088cc; }
        .btn { background: #0088cc; color: white; padding: 10px 20px; border-radius: 10px; border: none; }
    </style>
</head>
<body>
    <h1>🛍 Pekin Tovar Do'koniga xush kelibsiz!</h1>
    <p>Tez kunda barcha mahsulotlar shu yerda chiqadi.</p>
    <button class="btn" onclick="tg.close()">Yopish</button>
    <script>
        let tg = window.Telegram.WebApp;
        tg.expand();
    </script>
</body>
</html>
