# 🚀 Sistemas Embebidos – Instalación y configuración del entorno

![ESP32](https://img.shields.io/badge/ESP32-DevKit%20V1-blue?logo=espressif)
![PlatformIO](https://img.shields.io/badge/PlatformIO-IDE-orange?logo=platformio)
![Wokwi](https://img.shields.io/badge/Wokwi-Simulation-purple)
![Arduino](https://img.shields.io/badge/Framework-Arduino-teal?logo=arduino)
![VS Code](https://img.shields.io/badge/Visual%20Studio%20Code-IDE-blue?logo=visualstudiocode)
![GitHub](https://img.shields.io/badge/GitHub-Version%20Control-black?logo=github)

---

## 📚 1. Introducción

En esta guía se describe el procedimiento para instalar y configurar el entorno de desarrollo utilizado en la asignatura de **Sistemas Embebidos**.

El entorno permitirá desarrollar, compilar, simular y posteriormente programar sistemas basados en **ESP32** utilizando:

- **Visual Studio Code**
- **PlatformIO IDE**
- **Arduino Framework**
- **Wokwi**
- **Git y GitHub**

El flujo general de trabajo será:

```text
                 SISTEMAS EMBEBIDOS
                          │
                          ▼
                 Visual Studio Code
                          │
                 ┌────────┴────────┐
                 │                 │
                 ▼                 ▼
            PlatformIO           Wokwi
                 │                 │
              Compilar          Simular
                 │                 │
                 └────────┬────────┘
                          ▼
                        ESP32
                          │
                          ▼
                       GitHub
