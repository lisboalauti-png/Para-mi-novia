# Para-mi-novia
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Para Vicky ❤️</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
    }
    .card {
      background: #fff;
      padding: 40px;
      border-radius: 25px;
      box-shadow: 0 8px 25px rgba(0,0,0,0.2);
      max-width: 500px;
      animation: aparecer 2s ease-in-out;
    }
    h1 {
      color: #e63946;
      font-size: 2.5em;
    }
    p {
      font-size: 1.3em;
      color: #444;
      margin-top: 15px;
    }
    .hearts {
      font-size: 2em;
      margin-top: 20px;
      animation: latido 1.2s infinite;
    }

    @keyframes aparecer {
      from { opacity: 0; transform: translateY(50px); }
      to { opacity: 1; transform: translateY(0); }
    }
    @keyframes latido {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>❤️ Te amo Vicky ❤️</h1>
    <p>Te amo vicky un montón y perdón por todo,<br>
    feliz mes 🫶🏾🫶🏾 te amooooo</p>
    <div class="hearts">💖💞💕</div>
  </div>
</body>
</html>
