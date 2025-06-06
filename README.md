<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HUB GAMING</title>
  <link rel="stylesheet" href="styles.css">
  <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap');
    body {
      font-family: 'Arial', sans-serif;
      color: #333;
      margin: 0;
      padding: 0;
    }
    #background-video {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: -1;
    }
    @keyframes gradientBG {
        0% { background: linear-gradient(135deg, #e0f7fa, #c5e1a5); }
        25% { background: linear-gradient(135deg, #c5e1a5, #b2dfdb); }
        50% { background: linear-gradient(135deg, #b2dfdb, #81c784); }
        75% { background: linear-gradient(135deg, #81c784, #f8bbd0); }
        100% { background: linear-gradient(135deg, #f8bbd0, #e0f7fa); }
    }
    .container {
      max-width: 800px;
      margin: 20px auto;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
      animation: gradientBG 15s infinite alternate ease-in-out;
      background-size: 200% 200%;
    }
    header {
      text-align: center;
      margin-bottom: 20px;
    }
    .avatar img {
      width: 250px;
      border-radius: 50%;
      border: 3px solid #4CAF50;
    }
    h1 {
      font-family: 'Orbitron', sans-serif;
      font-size: 3em;
      margin: 10px 0;
      background: linear-gradient(90deg, #ff8c00, #ff0080);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }
    h2 {
      color: #333;
      font-size: 2em;
      margin: 20px 0 10px;
    }
    p {
      max-width: 600px;
      margin: 0 auto;
      text-align: center;
    }
    .button {
      display: inline-block;
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s;
      margin: 20px 0;
    }
    .button:hover {
      background-color: #45a049;
    }
    .section {
      background-color: rgba(231, 243, 254, 0.8);
      padding: 15px;
      border-radius: 5px;
      margin: 20px 0;
    }
    footer {
      text-align: center;
      margin-top: 20px;
    }
    .social-media a {
      margin: 0 10px;
      text-decoration: none;
      color: #4CAF50;
      font-weight: bold;
    }
    .social-media a:hover {
      text-decoration: underline;
    }
    .video-section {
      margin: 20px 0;
      text-align: center;
    }
    .video-section video {
      width: 100%;
      max-width: 800px;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }
  </style>
</head>
<body>
  <video autoplay loop muted playsinline id="background-video">
    <source src="https://github.com/HuyBao2206/BIO/raw/fd852482e6beb927f5b1f108204e028f1fe9e9ac/9convert.com%20-%20Neon%20Rounded%20Purple%20lines%20Abstract%20Gradient%20Background%20Animation%20%20Free%20Version_1080p.mp4" type="video/mp4">
    Trình duyệt của bạn không hỗ trợ video.
  </video>
  <div class="container">
    <header>
      <div class="avatar">
        <img src="https://raw.githubusercontent.com/HuyBao2206/bao-huy/main/Thi%E1%BA%BFt%20k%E1%BA%BF%20ch%C6%B0a%20c%C3%B3%20t%C3%AAn.png" alt="Fk" />
      </div>
      <h1>HUB GAMING</h1>
      <p>Chào mừng bạn đến với HUB GAMING! Tại đây, bạn sẽ được giải trí với những video gameplay, review, livestream và chia sẻ kinh nghiệm thú vị. Hãy đăng ký và theo dõi mình trên mọi nền tảng để không bỏ lỡ những nội dung độc đáo mỗi ngày!</p>
      <a href="https://playerduo.net/hubgaming" class="button">Ủng hộ mình ở đây nhé!</a>
    </header>
    <section class="video-section">
      <video autoplay loop muted playsinline>
        <source src="https://raw.githubusercontent.com/HuyBao2206/BIO/main/biovideohubgaming.mp4" type="video/mp4">
        Trình duyệt của bạn không hỗ trợ video.
      </video>
    </section>
    <section class="section">
      <h2>Định hướng mà mình đang triển khai trên Tiktok :</h2>
      <p>- Nghiên cứu, biên dịch và chia sẻ trích dẫn ở nhiều chủ đề.</p>
      <p>- Khai thác Hacklife tips để đơn giản hóa mọi thứ.</p>
      <p>- Cảm ơn mọi người đã quan tâm, yêu thích và theo dõi mình trên Tiktok nhé!</p>
    </section>
    <section class="contact-info">
      <h2>Liên hệ công việc :</h2>
      <p>📍 Email: <a href="mailto:baohuy22062002@gmail.com">baohuy22062002@gmail.com</a></p>
      <p>☎️ Số điện thoại: 0795858142</p>
    </section>
    <footer>
      <div class="social-media">
        <h2>Theo dõi mình trên mạng xã hội :</h2>
        <a href="https://www.tiktok.com/@hub_gaming226?_t=ZS-8ugZgYJ97oX&_r=1" target="_blank">TikTok</a>
        <a href="https://www.facebook.com/cynical2206" target="_blank">Facebook</a>
        <a href="https://www.youtube.com/@baohuy2967" target="_blank">Youtube</a>
      </div>
    </footer>
  </div>
</body>
