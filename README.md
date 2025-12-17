# Birthday-card2.0
https://your-username.github.io/birthday-card/
birthday-card/
│
├── index.html
├── style.css
└── script.js
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday 🎉</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="card">
  <h1>🎂 Happy Birthday! 🎉</h1>
  <p>Wishing you a day filled with love & joy 💖</p>

  <div class="cake">
    <div class="candles">
      <div class="flame"></div>
      <div class="flame"></div>
      <div class="flame"></div>
    </div>
    <div class="cake-body"></div>
  </div>

  <button onclick="blowCandles()">🎈 Blow Candles</button>
</div>

<script src="script.js"></script>
</body>
</html>
body {
  background: linear-gradient(to right, #ff9a9e, #fad0c4);
  font-family: Arial, sans-serif;
  text-align: center;
}

.card {
  margin-top: 50px;
  background: white;
  padding: 30px;
  border-radius: 15px;
  width: 300px;
  margin-left: auto;
  margin-right: auto;
  box-shadow: 0 10px 20px rgba(0,0,0,0.2);
}

.cake {
  margin: 20px auto;
}

.cake-body {
  width: 200px;
  height: 100px;
  background: #8b4513;
  border-radius: 10px;
  margin: auto;
}

.candles {
  display: flex;
  justify-content: center;
  gap: 20px;
  margin-bottom: -10px;
}

.flame {
  width: 10px;
  height: 20px;
  background: orange;
  border-radius: 50%;
  animation: flicker 0.5s infinite alternate;
}

@keyframes flicker {
  from { opacity: 1; }
  to { opacity: 0.6; }
}

button {
  padding: 10px 20px;
  font-size: 16px;
  background: #ff4081;
  color: white;
  border: none;
  border-radius: 10px;
  cursor: pointer;
}
