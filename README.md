<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fadivs | Соц.сети</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(180deg, #1a0826, #3d1f5c);
      color: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }

    .card {
      background: #1e1e2f;
      border-radius: 20px;
      padding: 20px;
      width: 350px;
      text-align: center;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.6);
      animation: fadeIn 1s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .avatar img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #7a3cff;
      transition: transform 0.3s;
    }

    .avatar img:hover {
      transform: scale(1.05);
    }

    h1 {
      margin: 15px 0 5px;
      font-size: 24px;
    }

    p.desc {
      font-size: 14px;
      color: #bbb;
      margin-bottom: 20px;
    }

    .links a {
      display: flex;
      align-items: center;
      justify-content: space-between;
      background: #2a2a3d;
      color: #fff;
      text-decoration: none;
      padding: 12px 15px;
      margin: 8px 0;
      border-radius: 10px;
      font-size: 16px;
      transition: background 0.3s, transform 0.3s, box-shadow 0.3s;
    }

    .links a:hover {
      background: #3d3d55;
      transform: translateY(-3px);
      box-shadow: 0 5px 15px rgba(122, 60, 255, 0.5);
    }

    .links img {
      width: 24px;
      height: 24px;
      margin-right: 10px;
    }

    .icon-text {
      display: flex;
      align-items: center;
    }

    .verified {
      color: #3fa9ff;
      margin-left: 5px;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="avatar">
      <img src="avatar.png" alt="Fadivs">
    </div>
    <h1>Fadivs</h1>
    <p class="desc">Стример • Блогер • Батя</p>

    <div class="links">
      <a href="https://twitch.tv/fadivs" target="_blank">
        <span class="icon-text"><img src="https://cdn-icons-png.flaticon.com/512/5968/5968819.png">Twitch</span>
        <span class="verified">✔</span>
      </a>
      <a href="https://t.me/fadisoska" target="_blank">
        <span class="icon-text"><img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png">Telegram</span>
        <span class="verified">✔</span>
      </a>
      <a href="https://youtube.com/@fadivs?si=PNrAG9W2egK4eeYt" target="_blank">
        <span class="icon-text"><img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png">YouTube</span>
        <span class="verified">✔</span>
      </a>
      <a href="https://kick.com/fadivs/about" target="_blank">
        <span class="icon-text"><img src="https://cdn-icons-png.flaticon.com/512/5968/5968875.png">Kick</span>
        <span class="verified">✔</span>
      </a>
      <a href="https://www.tiktok.com/@fadivs?_t=ZM-8z8raGqNFqf&_r=1" target="_blank">
        <span class="icon-text"><img src="https://cdn-icons-png.flaticon.com/512/3046/3046121.png">TikTok</span>
        <span class="verified">✔</span>
      </a>
      <a href="https://www.instagram.com/fadivs?igsh=MWJ5Z2t6Y3J4YXF3bw==" target="_blank">
        <span class="icon-text"><img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png">Instagram</span>
        <span class="verified">✔</span>
      </a>
    </div>
  </div>
</body>
</html>
