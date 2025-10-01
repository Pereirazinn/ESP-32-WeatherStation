# 🌤️ ESP32 Weather Station
![Platform](https://img.shields.io/badge/platform-ESP32-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-working-brightgreen)

Uma estação meteorológica IoT baseada no **ESP32**, desenvolvida no âmbito da disciplina  
*PII - Laboratório de Hardware para CIB (ISTEC Porto)*.

📊 Mede **temperatura, humidade e movimento**, apresentando os dados:
- Num **ecrã OLED** em tempo real
- Numa **interface web responsiva** via rede Wi-Fi

---

## 🚀 Funcionalidades
- 🌡️ Leitura de temperatura (DHT11)  
- 💧 Leitura de humidade (DHT11)  
- 🕺 Deteção de movimento (SR501)  
- 📺 Display OLED com animações e ícones  
- 🌐 Servidor Web via Wi-Fi com atualização em tempo real  

---

## 🔧 Hardware Necessário
- ESP32 DevKit  
- Sensor DHT11  
- Sensor PIR SR501  
- OLED SSD1306  
- Breadboard + resistores + cabos  

---

## 🔌 Esquema de Ligações
*(exemplo — substitui com a tua imagem em `/assets/circuit.png`)*

![Circuito](assets/circuit.png)

---

## ⚙️ Instalação e Uso

```bash
# 1. Clonar o repositório
git clone https://github.com/seu-usuario/ESP32-WeatherStation.git

# 2. Abrir o projeto no Arduino IDE

# 3. Instalar as bibliotecas necessárias:
#    - WiFi.h
#    - DHT.h
#    - Adafruit SSD1306
#    - Adafruit GFX
#    - ESPAsyncWebServer
#    - AsyncTCP

# 4. Carregar o código para o ESP32

# 5. Conectar-se ao Wi-Fi criado:
SSID: WeatherStation
PASS: Weather1234
