# KostkaLED v2.4

KostkaLED is an ESP32-S2 based LED cube project designed around the Wemos D1 mini and a HUB75 64×64 RGB panel. The firmware provides a browser-accessible control panel alongside several built-in animations and clock displays.

## Features

- **Web control panel** for switching display modes, adjusting brightness, and selecting transition effects.
- **Animation presets** including:
  - Fire
  - Rainbow
  - Clock + Skull
  - Analog Clock
- **Dark analog clock background** for improved legibility.
- **Daily effect rotation** that randomly selects a new preset every 24 hours.
- **Persistent USB CDC logging** so serial logs are available immediately after restart.
- **Optional 3×2 VirtualMatrix** (six panels) configuration when chaining HUB75 panels in series.

## Dependencies

The project relies on the following Arduino libraries:

- [`ESP32-HUB75-MatrixPanel-I2S-DMA`](https://github.com/mrfaptastic/ESP32-HUB75-MatrixPanel-I2S-DMA) by mrfaptastic.
- *(Optional)* [`VirtualMatrixPanel`](https://github.com/mrfaptastic/ESP32-HUB75-MatrixPanel-I2S-DMA/tree/master/examples/VirtualMatrixPanel) by the same author for multi-panel support.

## Hardware

- ESP32-S2 Wemos D1 mini.
- HUB75 64×64 LED matrix panel.
- *(Optional)* Additional HUB75 panels for VirtualMatrix setups.

