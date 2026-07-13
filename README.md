# BoomFFA-Shop
<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Minecraft Server Shop</title>
<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #111;
    color: white;
    text-align: center;
}

header {
    background: #1f8b2c;
    padding: 30px;
}

h1 {
    margin: 0;
    font-size: 40px;
}

.shop {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
    margin: 40px;
}

.card {
    background: #222;
    border: 2px solid #1f8b2c;
    border-radius: 15px;
    padding: 25px;
    width: 220px;
}

.price {
    font-size: 25px;
    color: #00ff55;
}

button {
    background: #1f8b2c;
    color: white;
    border: none;
    padding: 12px 25px;
    border-radius: 8px;
    cursor: pointer;
    font-size: 16px;
}

button:hover {
    background: #28c93f;
}

.discord {
    margin: 30px;
}

.discord a {
    color: white;
    background: #5865F2;
    padding: 15px 30px;
    border-radius: 10px;
    text-decoration: none;
}
</style>
</head>

<body>

<header>
<h1>⛏ Minecraft Server Shop</h1>
<p>Rüste dich mit neuen Rängen aus!</p>
</header>

<div class="shop">

<div class="card">
<h2>VIP</h2>
<p class="price">4,99€</p>
<p>⭐ VIP Rang</p>
<button onclick="buy('VIP')">Mit Paysafe bezahlen</button>
</div>

<div class="card">
<h2>VIP+</h2>
<p class="price">6,99€</p>
<p>⭐ VIP+ Rang</p>
<button onclick="buy('VIP+')">Mit Paysafe bezahlen</button>
</div>

<div class="card">
<h2>Boom</h2>
<p class="price">8,99€</p>
<p>💥 Boom Rang</p>
<button onclick="buy('Boom')">Mit Paysafe bezahlen</button>
</div>

<div class="card">
<h2>Boom+</h2>
<p class="price">10,99€</p>
<p>💥 Boom+ Rang</p>
<button onclick="buy('Boom+')">Mit Paysafe bezahlen</button>
</div>

</div>

<div class="discord">
<h2>Unser Discord</h2>
<a href="https://discord.gg/FsNHRr4xW" target="_blank">
Discord beitreten
</a>
</div>

<script>
function buy(rank) {
    alert("Du hast " + rank + " ausgewählt.\n\nZahlung: Paysafe Karte\n\nKontaktiere den Server-Admin nach der Zahlung für die Freischaltung.");
}
</script>

</body>
</html>
