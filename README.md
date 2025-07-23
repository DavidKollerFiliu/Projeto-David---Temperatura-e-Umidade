<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
</head>
<body>
  <h1>Projeto David - ESP32 - Monitoramento de Temperatura e Umidade com Blynk</h1>

  <p>Este projeto utiliza um ESP32 para monitorar <strong>temperatura e umidade</strong> com um sensor DHT22, exibir os dados em um <strong>LCD I2C</strong>, salvar leituras em um <strong>cartão microSD</strong> e controlar <strong>LEDs remotamente via Blynk</strong>.</p>

  <h2>📦 Recursos Utilizados</h2>
  <ul>
    <li>ESP32</li>
    <li>Sensor DHT22</li>
    <li>LCD I2C (16x2)</li>
    <li>Cartão MicroSD</li>
    <li>Blynk IoT Platform</li>
    <li>Dois LEDs (verde e azul)</li>
    <li>Conexão Wi-Fi via Wokwi-GUEST</li>
  </ul>

  <h2>⚙️ Funcionalidades</h2>
  <ul>
    <li>Controle remoto dos LEDs ou Relés via Blynk (V0 e V1)</li>
    <li>Leitura de temperatura e umidade a cada 2 segundos</li>
    <li>Exibição dos dados no LCD I2C</li>
    <li>Gravação e leitura dos dados no cartão microSD</li>
    <li>Alertas via Blynk para alta temperatura (&gt; 50°C) e alta umidade (&gt; 70%)</li>
  </ul>

  <h2>🚀 Como Funciona</h2>
  <ul>
    <li>Conecta automaticamente à rede Wi-Fi e à plataforma Blynk</li>
    <li>Lê dados do sensor DHT22</li>
    <li>Exibe os dados no Serial Monitor e no LCD</li>
    <li>Salva as medições em um arquivo <code>log.txt</code> no cartão microSD</li>
    <li>Gera alertas se a temperatura ou a umidade ultrapassarem os limites definidos</li>
    <li>Os LEDs podem ser acionados remotamente através do app Blynk</li>
  </ul>

  <h2>📌 Observações</h2>
  <ul>
    <li>O projeto usa o Wi-Fi “Wokwi-GUEST” sem senha</li>
    <li>Os dados do sensor são enviados para os pinos virtuais V2 (temperatura) e V3 (umidade) do Blynk</li>
    <li>Certifique-se de que o cartão microSD esteja corretamente conectado ao pino CS (GPIO 5)</li>
    <li>Os LEDs conectados aos pinos 14 (verde) e 12 (azul) são controlados pelos botões V0 e V1 do aplicativo Blynk</li>
  </ul>

  <h2>📊 Resultados</h2>
  <ul>
    <li>Temperatura: 26.5°C</li>
    <li>Umidade: 52.3%</li>
    <li>Dados gravados com sucesso no MicroSD local</li>
    <li>Dados enviados para Servidor Blynk</li>
    <li>Controle pelo celular através do app Blynk</li>
    <li>Acionamento de LEDs ou Relés via Blynk</li>
    <li>Visualização de gráficos e medições via LCD</li>
    <li>Visualização de medições via Blynk</li>
    <li>Recebimento de alertas via Blynk para alta temperatura (&gt; 50°C) e alta umidade (&gt; 70%)</li>
  </ul>
</body>
</html>


