<!DOCTYPE html>
<html lang="pt-BR">
<head> … estilos … </head>
<body>
  <div class="container">
    <h1>🔥 Vaso de Honra – Palavra Profética 🔥</h1>
    <div class="versiculo" id="versiculo">Carregando unção...</div>
    <iframe style="display:none;" src="https://www.youtube.com/embed/bWUaznyZLd0?autoplay=1&loop=1&playlist=bWUaznyZLd0" allow="autoplay" ></iframe>
    <div class="qr-code">
      <p>Escaneie e compartilhe esta unção:</p>
      <img id="qr" src="" alt="QR Code">
    </div>
  </div>
  <script>
    const versiculos = [/* 100 frases bíblicas */];
    document.getElementById('versiculo').textContent = versiculos[Math.floor(Math.random() * versiculos.length)];
    const domain = 'https://<SEU_USUARIO>.github.io';
    document.getElementById('qr').src = 'https://api.qrserver.com/v1/create-qr-code/?data=' + encodeURIComponent(domain) + '&size=200x200';
  </script>
</body>
</html>
