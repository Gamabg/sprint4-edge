<h1 align="center">⚽ Detector de Gol Inteligente</h1>

<p align="center">
  <b>Projeto IoT com ESP32, LDR e DHT11</b><br>
  <i>Detecção automática de gols e monitoramento ambiental durante o jogo</i>
</p>

<p align="center">
  <img src="" width="80%" alt="Imagem ilustrativa do gol e sensores"/>
</p>

---

<h2>🧠 Sobre o Projeto</h2>

Este projeto implementa um sistema inteligente capaz de detectar automaticamente quando a bola cruza a linha do gol, utilizando sensores de luminosidade (<b>LDR</b>) e sensores ambientais (<b>DHT11</b>).  
O sistema foi desenvolvido em <b>ESP32</b> ou <b>Arduino</b>, podendo futuramente integrar comunicação <b>MQTT</b> e dashboards em tempo real.

---

<h2>🎯 Objetivos</h2>

✅ Detectar a passagem da bola com o sensor <b>LDR</b><br>
✅ Monitorar temperatura e umidade com o sensor <b>DHT11</b><br>
✅ Utilizar o <b>ESP32</b> ou <b>Arduino</b> como unidade de controle<br>
✅ Indicar gols detectados por meio de <b>LEDs</b><br>
✅ Possibilitar expansões com dashboards e visão computacional

---

<h2>🧩 Arquitetura do Sistema</h2>

<p align="center">
  <img src="https://cdn.pixabay.com/photo/2017/08/26/13/40/soccer-2687907_1280.jpg" width="75%" alt="Arquitetura do sistema de detecção de gol"/>
</p>

| Camada | Tecnologia | Descrição |
|--------|-------------|-----------|
| Microcontrolador | **ESP32 / Arduino** | Processa os dados e controla os sensores |
| Sensores | **LDR / DHT11** | Detectam passagem da bola e condições ambientais |
| Atuadores | **LEDs** | Indicam visualmente o gol detectado |
| Comunicação | **Serial / MQTT (futuro)** | Envio de dados e integração com dashboards |

---

<h2>🧠 Funcionamento</h2>

O sensor <b>LDR</b> é posicionado na trave ou linha do gol.  
Quando a bola passa, ocorre uma queda brusca na luminosidade captada — esse evento é interpretado como um <b>gol detectado</b>.  

O sensor <b>DHT11</b> coleta dados de temperatura e umidade, permitindo análises sobre as condições ambientais que podem influenciar o desempenho da partida.

---

<h2>🔧 Componentes Utilizados</h2>

<ul>
  <li>Sensor de luminosidade (LDR)</li>
  <li>Sensor de temperatura e umidade (DHT11)</li>
  <li>ESP32 ou Arduino</li>
  <li>LEDs para indicar gol detectado</li>
  <li>Resistores e jumpers</li>
</ul>

---

<h2>🚀 Aplicações Futuras</h2>

<ul>
  <li>📡 Comunicação via MQTT com dashboards em tempo real</li>
  <li>📱 Aplicativos móveis para exibição de estatísticas</li>
  <li>🎥 Uso de visão computacional para aprimorar a detecção</li>
</ul>

---

<h2>❤️ Agradecimentos</h2>

<p align="center">
  Projeto desenvolvido por <b>[Seu Nome]</b><br>
  <i>Projeto acadêmico de IoT e Automação Esportiva</i><br><br>
  Agradecemos seu interesse em recriar e aprimorar este sistema! 👋<br>
  <i>Sinta-se à vontade para expandir o projeto com novos sensores e recursos.</i>
</p>
