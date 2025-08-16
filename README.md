<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Convite - Aniversário</title>
  <style>
    body {
      font-family: 'Comic Sans MS', cursive, sans-serif;
      background: linear-gradient(135deg, #ff66cc, #66ccff, #99ff99);
      color: #fff;
      text-align: center;
      padding: 30px;
      overflow-x: hidden;
    }
    .card {
      background: rgba(0,0,0,0.5);
      border-radius: 25px;
      padding: 30px;
      box-shadow: 0 0 30px rgba(0,0,0,0.4);
      animation: aparecer 2s ease;
      max-width: 600px;
      margin: auto;
    }
    h1 {
      font-size: 2.5rem;
      animation: piscar 2s infinite alternate;
    }
    p {
      font-size: 1.2rem;
    }
    .btn {
      display: inline-block;
      margin-top: 25px;
      padding: 15px 30px;
      background: #ff3399;
      color: white;
      font-size: 1.3rem;
      border-radius: 40px;
      text-decoration: none;
      transition: 0.3s;
      box-shadow: 0 5px 15px rgba(0,0,0,0.3);
    }
    .btn:hover {
      background: #cc0066;
      transform: scale(1.1);
    }
    .hero {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-bottom: 20px;
      flex-wrap: wrap;
    }
    .hero img {
      width: 120px;
      transition: transform 0.4s;
    }
    .hero img:hover {
      transform: scale(1.2) rotate(-5deg);
    }
    @keyframes piscar {
      from { color: #fff; }
      to { color: #ffcc00; }
    }
    @keyframes aparecer {
      from { opacity: 0; transform: scale(0.8); }
      to { opacity: 1; transform: scale(1); }
    }
  </style>
</head>
<body>

  <!-- Música de Fundo (embed) -->
  <div style="margin-bottom:20px;">
    <iframe src="https://archive.org/embed/tvtunes_517" width="100%" height="100" frameborder="0" allowfullscreen></iframe>
  </div>

  <div class="card">
    <div class="hero">
      <img src="https://upload.wikimedia.org/wikipedia/en/9/9a/Bubbles_PPG1998.png" alt="Lindinha">
      <img src="https://upload.wikimedia.org/wikipedia/en/5/5a/Blossom_PPG1998.png" alt="Florzinha">
      <img src="https://upload.wikimedia.org/wikipedia/en/1/10/Buttercup_PPG1998.png" alt="Docinho">
    </div>

    <h1>🎉 Você foi convocado! 🎉</h1>
    <p>💖💙💚 As Meninas Superpoderosas precisam de você no meu aniversário!</p>

    <p><strong>Data:</strong> 07/09/2025</p>
    <p><strong>Hora:</strong> 11h</p>
    <p><strong>Local:</strong> Rua Fidelo Mariano de Almeida, 688 – Oliveira 2</p>
    <p><strong>Aniversariantes:</strong> Isadora, Analis e Lúcy Maria</p>

    <a class="btn" href="https://wa.me/5567992442732?text=Olá,+confirmo+minha+presença+no+aniversário++das+Meninas+Superpoderosas!">
      Confirmar Presença no WhatsApp
    </a>
  </div>
</body>
</html>
