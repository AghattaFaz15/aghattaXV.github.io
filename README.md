<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Aghatta Faz XV – Palavra Profética</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: 
        linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
        url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1600&q=80') no-repeat center center fixed;
      background-size: cover;
      color: white;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
      padding: 2rem;
    }

    h1 {
      font-size: 2.8rem;
      color: #ffae42;
      text-shadow: 2px 2px #000;
      margin-bottom: 1rem;
    }

    .versiculo {
      font-size: 1.4rem;
      background-color: rgba(0,0,0,0.5);
      padding: 1rem 2rem;
      border-radius: 12px;
      box-shadow: 0 0 15px #ffae42;
      max-width: 800px;
      margin-top: 2rem;
    }

    iframe {
      margin-top: 2rem;
      border-radius: 12px;
      width: 100%;
      max-width: 560px;
      height: 315px;
      box-shadow: 0 0 30px #ff6a00cc;
    }
  </style>
</head>
<body>
  <h1>Aghatta Faz XV – Toque do Céu 🕊️</h1>

  <p class="versiculo" id="versiculo">Carregando palavra profética...</p>

  <iframe 
    src="https://www.youtube.com/embed/bWUaznyZLd0?autoplay=1&loop=1&playlist=bWUaznyZLd0" 
    title="Louvor Profético" 
    allow="autoplay; encrypted-media" 
    allowfullscreen>
  </iframe>

  <script>
    const versiculos = [
      "Deus vai surpreender tua casa com milagres ainda este ano! – Isaías 43:19",
      "O que era lágrima vai virar testemunho! – Salmo 126:5",
      "A promessa está de pé, ainda que tudo diga não. – Números 23:19",
      "Há um novo tempo de colheita chegando sobre tua vida! – Gálatas 6:9",
      "O vento soprou e trouxe resposta de Deus! – João 3:8",
      "A batalha está acirrada porque a vitória é grande! – 2 Crônicas 20:17",
      "Receba dupla honra onde houve vergonha. – Isaías 61:7",
      "Ainda hoje Deus muda decretos a teu favor! – Ester 8:5",
      "Você não está sozinho. O céu te guarda! – Salmo 91:11",
      "A última palavra vem do Senhor! – Provérbios 16:1"
    ];

    const aleatorio = versiculos[Math.floor(Math.random() * versiculos.length)];
    document.getElementById('versiculo').textContent = aleatorio;
  </script>
</body>
</html>
