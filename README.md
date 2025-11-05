<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Oi! Eu sou a Lorena 💜</title>

<!-- Fonte pixelada -->
<link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">

<style>
  body {
    background-color: #0d0d1a;
    color: #c77dff;
    font-family: 'Press Start 2P', monospace;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
  }

  .container {
    display: flex;
    align-items: center;
    gap: 40px;
  }

  .typing {
    font-size: 18px;
    white-space: nowrap;
    overflow: hidden;
    border-right: 4px solid #c77dff;
    width: 0;
    animation: typing 4s steps(25, end) forwards, blink 0.7s infinite;
  }

  @keyframes typing {
    from { width: 0; }
    to { width: 330px; } /* Ajusta o tamanho pra caber o texto completo */
  }

  @keyframes blink {
    50% { border-color: transparent; }
  }

  .gif img {
    width: 220px;
    border-radius: 10px;
  }
</style>
</head>

<body>
  <div class="container">
    <div class="typing">Oi! Eu sou a Lorena 💜</div>
    <div class="gif">
      <img src="https://media.giphy.com/media/0U7bWQK9s75PjRKcHz/giphy.gif" alt="Gif pixelado">
    </div>
  </div>
</body>
</html>

