# MSPM0G3507 Board

Ein KiCad-Projekt: kompaktes Entwicklungsboard rund um den **TI MSPM0G3507SPTR**.

<!-- TODO: Foto oder 3D-Render des Boards einfügen -->
<!-- ![Board](docs/board.png) -->

## ✨ Features

- **MCU:** MSPM0G3507SPTR – Arm Cortex-M0+ mit bis zu 80 MHz, 128 KB Flash, 32 KB SRAM
- **Peripherie des Chips:** CAN-FD, 12-Bit-ADC, DAC, Op-Amp, UART, SPI, I²C
- TODO: Stromversorgung (z. B. USB-C, 3,3-V-Regler)
- TODO: Programmierung/Debugging (z. B. SWD-Header)
- TODO: Herausgeführte Pins, LEDs, Taster, Sensoren

## 📁 Projektstruktur

```text
.
├── *.kicad_pro      # KiCad-Projekt
├── *.kicad_sch      # Schaltplan
├── *.kicad_pcb      # Platinenlayout
├── libs/            # Symbole & Footprints (falls vorhanden)
└── README.md
```

## 🚀 Loslegen

1. Repository klonen:
   ```bash
   git clone https://github.com/ErnestoCZ/KiCAD_MSPM0G3507SPTR_Board.git
   ```
2. Projektdatei `*.kicad_pro` in [KiCad](https://www.kicad.org/) öffnen (TODO: Version angeben, z. B. 8.x).
3. Schaltplan und Layout ansehen, bei Bedarf Gerber-Dateien exportieren.

## 🔧 Firmware

Der MSPM0G3507 wird mit dem [TI MSPM0 SDK](https://www.ti.com/tool/MSPM0-SDK) und Code Composer Studio (oder einer Toolchain deiner Wahl) programmiert.

## 📌 Status

TODO: z. B. „Prototyp in Arbeit“ / „Rev. A bestellt“ / „getestet“

## 📄 Lizenz

TODO: Lizenz wählen (z. B. CERN-OHL-P für Hardware, MIT für Code)
