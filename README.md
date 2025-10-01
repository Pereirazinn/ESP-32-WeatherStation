# 🌤️ ESP32 Weather Station
![Platform](https://img.shields.io/badge/platform-ESP32-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-working-brightgreen)

Uma estação meteorológica IoT baseada no **ESP32**.

## 📊 Intordução:
Este projeto tem como objetivo construir uma estação meteorológica baseada no **ESP32**,
capaz de coletar dados ambientais através de sensores digitais como o **DHT11**(sensor
de temperatura e humidade) e como o sensor **SR501**(sensor de movimento) e
exibi-los em tempo real através de uma interface web acessível via rede local. O
projeto visa aplicar conhecimentos práticos de eletrônica digital, sensores,
comunicação de dados e programação embarcada

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

[Circuito]<img width="1536" height="1024" alt="ChatGPT Image 1_10_2025, 12_05_42" src="https://github.com/user-attachments/assets/8cfb5168-e6f0-4528-9d79-f4f90dd28b31" />


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
