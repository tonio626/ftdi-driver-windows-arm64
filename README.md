# Guida completa per l’installazione dei driver FTDI per Windows ARM64 con Parallels Desktop 19

Questa guida spiega come installare i driver FTDI su Windows ARM64 eseguito in una VM tramite **Parallels Desktop 19** su Mac con processore Apple Silicon (M1, M2, M3).

## 🧰 Requisiti

- Mac Apple Silicon (M1, M2, M3…)
- Parallels Desktop 19 con VM Windows ARM64
- Connessione a Internet

## 📥 Download dei driver FTDI

1. Vai su: https://ftdichip.com/drivers/
2. Scarica il file: `CDM-v2.12.36.4-for-ARM64-Signed-Distibutable.zip`
3. Estrai il file **nella VM**, non sul desktop condiviso.

## 🛠️ Installazione manuale

1. Collega la scheda (es. Digilent Cmod A7)
2. Apri **Gestione Dispositivi** su Windows
3. Se appare un'icona gialla:
   - Tasto destro → *Aggiorna driver*
   - Seleziona: *Cerca i driver nel computer*
   - Indica la cartella con i file `.INF`
4. Completa l’installazione

## ✅ Verifica

- Se correttamente installato, il dispositivo apparirà come:
  - **USB Serial Converter** (in Controller USB)
  - **Porta COM** (se è attiva VCP)

## 🔗 Collegamento a Vivado

1. Collega la scheda via USB
2. In Vivado: `Open Hardware Manager → Open Target → Auto Connect`

## 🌐 Versione web + download PDF

👉 [Apri la guida come pagina web](https://tonio626.github.io/ftdi-driver-windows-arm64/)

📄 [Scarica la guida in PDF](Guida_installazione_Driver_FTDI_per_Windows_ARM64.pdf)


