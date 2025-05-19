# 🔋 Neey Battery Balancer Monitor

Gateway per bilanciatori Neey che legge i dati via UART e li pubblica su MQTT con integrazione automatica **Home Assistant**. Il dispositivo è configurabile tramite file `config.txt` su scheda SD.

---

## 🚀 Funzionalità

- Lettura dati da Balancer Neey (via 485)
- Pubblicazione su MQTT con supporto per:
  - Tensione totale e media
  - Delta massimo tra celle
  - Celle con valori estremi
  - Stato del sistema
  - Corrente di bilanciamento
  - Tensioni di ogni cella (fino a 24)
- Integrazione automatica con Home Assistant tramite **MQTT Discovery**
- Configurazione completa da SD card (`config.txt`)
- Riconnessione automatica a WiFi e MQTT

---

## 🧰 Requisiti hardware

- ESP32 Wroom32
- Una card micro-SD
- Connessione WiFi
- BMS Neey (modificato con interfaccia 485)

---
Il progetto è in fase di sviluppo, in futuro sarà possibile richiedere i circuiti stampati da assemblare o già pronti al uso
Per informazioni o richieste: https://t.me/+ZttQPkNAbGRiYmM8
