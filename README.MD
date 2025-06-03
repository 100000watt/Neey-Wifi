🔋 Neey Battery Balancer Monitor/Gateway for Home Assistant 

A gateway for Neey balancers that reads data via UART and publishes it to MQTT with automatic Home Assistant integration. The device is configurable via a config.txt file on an SD card or through the serial interface.

🚀 Features

    Reads data from Neey Balancer (via RS-485)
    Publishes to MQTT with support for:
        Total and average voltage
        Maximum delta between cells
        Cells with minimum and maximum values
        System status
        Balancing current
        Voltage of each cell (up to 24)
    Automatic integration with Home Assistant via MQTT Discovery
    Full configuration via SD card (config.txt)
    Configuration via terminal through the USB port of the ESP module
    Automatic reconnection to WiFi and MQTT

🧰 Hardware Requirements
    ESP32 Wroom32
    A micro-SD card
    WiFi connection
    Neey BMS (modified with RS-485 interface)

For those seeking a very clean setup, PCBs for the project are available.
--- For more information or requests: https://t.me/+ZttQPkNAbGRiYmM8 ---


# 🔋 Neey Battery Balancer Monitor

Gateway per bilanciatori Neey che legge i dati via UART e li pubblica su MQTT con integrazione automatica **Home Assistant**. Il dispositivo è configurabile tramite file `config.txt` su scheda SD oppure da seriale.

---

## 🚀 Funzionalità

- Lettura dati da Balancer Neey (via 485)
- Pubblicazione su MQTT con supporto per:
  - Tensione totale e media
  - Delta massimo tra celle
  - Celle con valore min e max
  - Stato del sistema
  - Corrente di bilanciamento
  - Tensioni di ogni cella (fino a 24)
- Integrazione automatica con Home Assistant tramite **MQTT Discovery**
- Configurazione completa da SD card (`config.txt`)
- Possibilità di configurazione tramite terminal tramite la porta USB del modulo ESP
- Riconnessione automatica a WiFi e MQTT

---

## 🧰 Requisiti hardware

- ESP32 Wroom32
- Una card micro-SD
- Connessione WiFi
- BMS Neey (modificato con interfaccia 485)

---
Per chi volesse un lavoro molto pulito sono disponibili i circuiti stampati del progetto
--- Per informazioni o richieste: https://t.me/+ZttQPkNAbGRiYmM8 ---
