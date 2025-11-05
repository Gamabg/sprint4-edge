<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Detector de Gol - Projeto com DHT11 e LDR</title>
  <style>
    body {
      font-family: "Heebo", sans-serif;
      background: linear-gradient(135deg, #0a0a23, #1b1b3a);
      color: #fff;
      text-align: center;
      padding: 40px 20px;
    }
    h1 {
      color: #00aaff;
      margin-bottom: 10px;
    }
    h2 {
      margin-top: 30px;
      color: #ffaa00;
    }
    p {
      max-width: 800px;
      margin: 0 auto 15px;
      line-height: 1.6;
    }
    .card {
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: 15px;
      padding: 20px;
      margin: 30px auto;
      max-width: 700px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.4);
    }
    footer {
      margin-top: 40px;
      font-size: 0.9em;
      opacity: 0.7;
    }
    img {
      width: 100%;
      border-radius: 12px;
      margin-top: 15px;
    }
  </style>
</head>
<body>

  <h1>⚽ Projeto: Detector de Gol Inteligente</h1>
  <p>Desenvolvido com sensores DHT11 e LDR para monitorar a passagem da bola e as condições ambientais durante o jogo.</p>

  <div class="card">
    <h2>🎯 Objetivo</h2>
    <p>O objetivo do projeto é criar um sistema capaz de detectar automaticamente quando a bola cruza a linha do gol. 
       Usando um sensor LDR, o sistema identifica a variação de luz provocada pela passagem da bola. 
       Além disso, o sensor DHT11 mede a temperatura e umidade do ambiente, fornecendo dados que podem influenciar no desempenho da partida.</p>
  </div>

  <div class="card">
    <h2>🧠 Funcionamento</h2>
    <p>O LDR (sensor de luminosidade) é posicionado na trave ou linha do gol. Quando a bola passa, há uma mudança brusca na intensidade de luz que o sensor capta — esse evento é interpretado como “gol detectado”.</p>
    <p>O DHT11 coleta temperatura e umidade, permitindo análises complementares sobre o ambiente de jogo.</p>
    <img src="https://cdn.pixabay.com/photo/2017/08/30/22/09/soccer-2691325_1280.jpg" alt="Imagem ilustrativa do gol e sensores">
  </div>

  <div class="card">
    <h2>🔧 Componentes Utilizados</h2>
    <ul style="list-style: none; padding: 0;">
      <li>• Sensor de luminosidade (LDR)</li>
      <li>• Sensor de temperatura e umidade (DHT11)</li>
      <li>• ESP32 ou Arduino</li>
      <li>• LEDs para indicar gol detectado</li>
      <li>• Resistores e jumpers</li>
    </ul>
  </div>

  <div class="card">
    <h2>🚀 Aplicações Futuras</h2>
    <p>O projeto pode evoluir para incluir comunicação com um servidor MQTT, integração com aplicativos móveis para mostrar estatísticas do jogo em tempo real e uso de visão computacional para aprimorar a detecção do gol.</p>
  </div>

  <footer>
    <p>Desenvolvido por [Seu Nome] — Projeto de IoT e Automação Esportiva</p>
  </footer>

</body>
</html>
