<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Buat Kamu yang Lagi Badmood 💖</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #f8b500, #fceabb);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
      color: #fff;
      animation: fadeIn 2s ease-in;
    }

    h1 {
      font-size: 3em;
      margin-bottom: 0.2em;
      text-shadow: 2px 2px rgba(0,0,0,0.2);
    }

    p {
      font-size: 1.4em;
      max-width: 600px;
      margin: 0 20px;
    }

    .heart {
      font-size: 3em;
      animation: heartbeat 1s infinite;
      margin-top: 20px;
    }

    .button {
      margin-top: 30px;
      padding: 12px 24px;
      background: #ff6f61;
      border: none;
      border-radius: 30px;
      color: #fff;
      font-size: 1em;
      cursor: pointer;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
      transition: background 0.3s ease;
    }

    .button:hover {
      background: #ff3b2e;
    }

    @keyframes heartbeat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-30px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <h1>Hei Kamu yang Lagi Badmood 😢</h1>
  <p>Hari ini mungkin nggak sempurna, tapi kamu tetap orang yang luar biasa. Jangan sedih lama-lama ya. Aku ada di sini untuk kamu selalu 💕</p>
  <div class="heart">💖</div>
  <button class="button" onclick="alert('Peluk virtual dulu! 🤗')">Klik kalau udah baikan 😘</button>
</body>
</html>
