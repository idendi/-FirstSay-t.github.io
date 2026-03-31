<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<title>Portfolio</title>

<style>
body {
    margin: 0;
    background: black;
    color: white;
    font-family: Arial, sans-serif;
    overflow-x: hidden;
}

.section {
    height: 100vh;
    display: flex;
    align-items: center;
    padding: 50px;
}

.big-text {
    font-size: 120px;
    font-weight: bold;
    line-height: 1;
    transition: 0.5s;
}

.big-text:hover {
    color: #3b82f6;
    transform: translateX(20px);
}

a {
    color: white;
    text-decoration: none;
}

.tg {
    position: fixed;
    bottom: 30px;
    right: 30px;
    background: white;
    color: black;
    padding: 15px 25px;
    border-radius: 30px;
    font-weight: bold;
}
</style>

</head>
<body>

<div class="section">
    <a href="https://t.me/yourusername" target="_blank">
        <div class="big-text">WRITE<br>ME</div>
    </a>
</div>

<div class="section">
    <div class="big-text">WEB<br>SITES</div>
</div>

<div class="section">
    <div class="big-text">DESIGN</div>
</div>

<a href="https://t.me/yourusername" target="_blank" class="tg">
    Telegram
</a>

</body>
</html>
