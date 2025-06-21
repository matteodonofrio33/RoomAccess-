🏠 RoomAccess+
RoomAccess+ è un sistema IoT basato su Arduino/ESP32 per l'automazione di una stanza. Include controllo accessi tramite tastierino, monitoraggio ambientale e funzioni smart gestibili anche da remoto tramite app.

🚀 Funzionalità principali
🔐 Apertura porta con password

📏 Rilevamento di presenza con sensore a ultrasuoni (HC-SR04)

🌡️ Misurazione temperatura e umidità

🚨 Sistema di allarme attivabile/disattivabile da app

📲 App mobile per il controllo remoto

💡 Accensione LED/tastierino in caso di poca luce

📊 Visualizzazione parametri su display LCD

🧰 Hardware utilizzato
Arduino Uno / ESP32 / Arduino R4 Wi-Fi

Tastierino alfanumerico 4x4

Sensore HC-SR04

Display LCD

Buzzer

LED e fotoresistore

DHT22 (temperatura/umidità)

Servomotore / Solenoide

Modulo Wi-Fi o Bluetooth

📦 Struttura del progetto
bash
Copia
Modifica
RoomAccess+
├── README.md
├── /arduino_code         → Codice per Arduino/ESP32
├── /mobile_app           → App o interfaccia remota (es. Blynk, MIT App Inventor)
├── /docs                 → Documentazione tecnica (requisiti, diagrammi, ecc.)
└── /media                → Immagini, foto e video demo
⚙️ Installazione
Carica il codice su Arduino/ESP32 con l’IDE Arduino

Collega l’hardware secondo lo schema fornito

Imposta le credenziali Wi-Fi nel file config.h (se presenti)

Apri il monitor seriale per il debug iniziale

Usa l’app mobile o tastierino per controllare il sistema

📱 App mobile
L’app può essere realizzata con:

MIT App Inventor

Blynk

Telegram Bot

Web App in HTML + JS

🛡️ Requisiti di sicurezza
Massimo 3 tentativi per password errata

Sistema di allarme attivabile

Log accessi

Pulsante di emergenza per reset

📸 Demo

(aggiungi immagini reali del progetto montato)

📝 Documentazione
Trovi l’analisi dei requisiti, il diagramma UML e altri documenti in /docs.

🙋‍♂️ Autore
Matteo D’Onofrio
Università degli Studi di Salerno
📧 [matteodonofrio003@gmail.com]


