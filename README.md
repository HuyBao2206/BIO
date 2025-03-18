<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HUB GAMING</title>
  <link rel="stylesheet" href="styles.css">
  <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #1a1a2e, #16213e, #0f3460);
      background-size: 400% 400%;
      animation: gradientBG 8s infinite alternate;
      color: #fff;
      overflow: hidden;
    }
    @keyframes gradientBG {
      0% { background-position: 0% 50%; }
      100% { background-position: 100% 50%; }
    }
    #particles-js {
      position: fixed;
      width: 100%;
      height: 100%;
      top: 0;
      left: 0;
      z-index: -1;
    }
    .container {
      max-width: 800px;
      margin: 50px auto;
      padding: 20px;
      border-radius: 8px;
      text-align: center;
      background: rgba(0, 0, 0, 0.7);
      box-shadow: 0 2px 10px rgba(255, 255, 255, 0.2);
    }
    .avatar img {
      width: 150px;
      border-radius: 50%;
      border: 3px solid #4CAF50;
    }
    h1 {
      font-size: 2.5em;
      color: #4CAF50;
    }
    .button {
      display: inline-block;
      padding: 10px 20px;
      background-color: #ff5733;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      transition: background 0.3s;
    }
    .button:hover {
      background: #c70039;
    }
  </style>
</head>
<body>
  <div id="particles-js"></div>
  <div class="container">
    <header>
      <div class="avatar">
        <img src="https://raw.githubusercontent.com/HuyBao2206/bao-huy/main/Thi%E1%BA%BFt%20k%E1%BA%BF%20ch%C6%B0a%20c%C3%B3%20t%C3%AAn.png" alt="Fk">
      </div>
      <h1>HUB GAMING</h1>
      <p>Chào mừng bạn đến với HUB GAMING! Tại đây, bạn sẽ được giải trí với những video gameplay, review, livestream và chia sẻ kinh nghiệm thú vị.</p>
      <a href="https://playerduo.net/hubgaming" class="button">Ủng hộ mình ở đây nhé!</a>
    </header>
  </div>
  <script>
    particlesJS("particles-js", {
      "particles": {
        "number": { "value": 100, "density": { "enable": true, "value_area": 800 } },
        "color": { "value": "#00ff00" },
        "shape": { "type": "circle" },
        "opacity": { "value": 0.5, "random": false },
        "size": { "value": 3, "random": true },
        "move": { "enable": true, "speed": 2 }
      },
      "interactivity": {
        "detect_on": "canvas",
        "events": { "onhover": { "enable": true, "mode": "repulse" } },
        "modes": { "repulse": { "distance": 100, "duration": 0.4 } }
      }
    });
  </script>
</body>
</html>
