# Aniversario-1<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Feliz Aniversário Rafa</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #ff9ecf, #ffc0cb);
      color: #fff;
      text-align: center;
    }

    h1 {
      margin-top: 40px;
      font-size: 3em;
    }

    p {
      max-width: 600px;
      margin: 20px auto;
      font-size: 1.2em;
    }

    .album {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 40px;
    }

    .foto {
      background: #fff;
      padding: 10px;
      border-radius: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      transform: rotate(-2deg);
      transition: 0.3s;
    }

    .foto:hover {
      transform: scale(1.05) rotate(0deg);
    }

    .foto img {
      width: 100%;
      border-radius: 10px;
    }

    footer {
      margin: 30px;
      font-size: 1em;
    }
  </style>
</head>
<body>

  <h1>🎉 Feliz Aniversário, Rafa! 🎂</h1>

  <p>
    Hoje celebramos não só o seu dia, mas também 4 anos de uma amizade incrível.
    Ao longo desse tempo, vivemos momentos inesquecíveis, cheios de risadas,
    parceria e cumplicidade. Que venham muitos e muitos anos pela frente,
    sempre com felicidade, conquistas e momentos especiais juntos. 💖
  </p>

  <div class="album">
    <div class="foto">
      <img src="foto1.png" alt="Foto 1">
    </div>
    <div class="foto">
      <img src="foto2.png" alt="Foto 2">
    </div>
    <div class="foto">
      <img src="foto3.png" alt="Foto 3">
    </div>
    <div class="foto">
      <img src="foto4.png" alt="Foto 4">
    </div>
  </div>

  <footer>
    Feito com carinho 💕
  </footer>

</body>
</html>
