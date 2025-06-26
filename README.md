# 🚀 MAINS-X: Modular AI Sensor Node - Xtreme

**MAINS-X** (Modular AI Sensor Node - Xtreme) is a compact, extensible, and high-performance development board purpose-built for **AI at the Edge**, **sensor fusion**, and **IoT prototyping**. It’s engineered using the powerful **ESP32-S3-WROOM-1** with optional **RP2040 co-processor** support, and includes rich peripherals like camera, MicroSD, QSPI flash, and more — all on a beautifully crafted 4-layer PCB.

---

## 🔩 Project Highlights

| Feature                      | Details                                                                 |
|-----------------------------|-------------------------------------------------------------------------|
| **Main MCU**                | ESP32-S3-WROOM-1 (WiFi + BLE + AI acceleration)                         |
| **AI Co-Processor**         | Optional RP2040 (via SPI/QSPI or I2C for ML acceleration tasks)         |
| **Memory & Storage**        | External QSPI Flash (W25Q128JVS), MicroSD Slot                          |
| **Power Options**           | USB-C & LiPo Battery with Fuel Gauge (MAX17048) + TPS65217 PMIC         |
| **Connectors**              | I²C Expansion, SPI Expansion, TPU Header, U.FL for external antenna     |
| **Peripherals**             | User LED, Button, Camera FFC Header (24-pin), Debug UART/GPIO Header   |
| **Power Protection**        | TVS diode, Schottky, Load switch                                        |
| **Board Design**            | 4-layer PCB, professional silkscreen, compact footprint, test pads      |
| **License**                 | Open-source under MIT License                                           |

---

## 🧠 Use Cases

- Edge AI / TinyML inference (TFLite Micro)
- Smart sensor logging & fusion
- Wearables & remote health monitoring
- Smart agriculture and climate sensing
- Robotics sensor hub
- Environmental data acquisition
- Real-time ML co-processing

---

## 📌 GPIO Pinout (ESP32-S3)

| Function       | ESP32-S3 Pin |
|----------------|--------------|
| I²C SDA        | GPIO8        |
| I²C SCL        | GPIO9        |
| QSPI Flash     | GPIO36–39    |
| MicroSD SPI    | GPIO40–43    |
| Camera         | GPIO18–21    |
| LED            | GPIO10       |
| Button         | GPIO0        |
| RP2040 Comm    | GPIO3, 4, 5   |
| UART Debug     | GPIO1, 2     |

_See full pin mapping in the schematic folder._

---

## 📦 BOM (Bill of Materials)

> The complete BOM is available in `/manufacturing/BOM.csv`.

Includes all passive and active components: TVS diode, PMIC, connectors, sensor headers, etc.

---

## 🌍 Open Source Commitment

This project is fully open-source and licensed under the [MIT License](./LICENSE).  
It is inspired by open hardware practices of **Adafruit**, **SparkFun**, **Pine64**, and **Seeed Studio**.

---

## 💬 Acknowledgements

- [Espressif Systems](https://espressif.com) for ESP32-S3
- [Raspberry Pi Foundation](https://raspberrypi.com) for RP2040
- [KiCad EDA](https://kicad.org) for open-source PCB design
- [OSHWA](https://oshwa.org) for promoting open hardware values

---

## 🚀 How to Contribute

- Star ⭐ the project
- Fork and submit PRs (hardware add-ons, routing improvements, etc.)
- Share builds using hashtag **#MAINSX**
- Submit issues or feature suggestions

---

## 📮 Contact

We welcome feedback and collaboration. Drop issues or pull requests — or share your own builds inspired by MAINS-X!

---

**Let’s make edge AI more accessible, open, and modular.**


