# MCCC — MeshCore CardComm

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-ESP32--S3-red.svg)
![Hardware](https://img.shields.io/badge/device-M5Stack%20Cardputer%20ADV-black.svg)
![LoRa](https://img.shields.io/badge/LoRa-CAP%20LoRa--1262-7B2CBF.svg)
![Status](https://img.shields.io/badge/status-private%20%E2%86%92%20open--source%20soon-orange.svg)

Cliente MeshCore para **M5Stack Cardputer ADV** con soporte **CAP LoRa-1262**. Diseñado para uso **standalone** (100% autónomo) o como **Bluetooth companion** junto a smartphone.

MeshCore client for **M5Stack Cardputer ADV** with **CAP LoRa-1262** support. Designed for **standalone** operation or as a **Bluetooth companion** connected to a smartphone.

---

## 🇪🇸 Español

### Características
- Interfaz gráfica TFT con temas y control de brillo.
- Scroll con `FN + ↑/↓`.
- Notificaciones por audio/pantalla.
- Fecha y hora por GPS/BT.
- Ajuste de *path hash*.
- Búsqueda de nodos/canales en tiempo real.
- Soporte CAP LoRa-1262 (basado en correcciones de `sosprz` e interfaz inspirada en `stachu`).

### Especificaciones

| Campo | Valor |
|---|---|
| Proyecto | MCCC — MeshCore CardComm |
| Autor principal | EA3IIU |
| Dispositivo objetivo | M5Stack Cardputer ADV |
| Radio | CAP LoRa-1262 |
| Modo de uso | Standalone / Bluetooth companion |
| Protocolo | MeshCore / LoRa Mesh |
| Licencia planificada | MIT |

### Estructura del repositorio

```
.
├── src/       # Código fuente principal (PlatformIO / Arduino)
├── lib/       # Librerías locales del proyecto
├── include/   # Cabeceras compartidas
├── assets/    # Recursos (imágenes, fuentes, sonidos)
├── docs/      # Documentación técnica y de usuario
└── .github/ISSUE_TEMPLATE.md
```

### Créditos
- Proyecto creado por **EA3IIU**.
- Soporte CAP LoRa-1262 basado en correcciones de **sosprz**.
- Diseño de interfaz inspirado en **stachu**.

### Disclaimer
Este proyecto es experimental y comunitario. No está afiliado oficialmente a M5Stack ni a MeshCore. No está diseñado para comunicaciones de emergencia o aplicaciones críticas.

---

## 🇬🇧 English

### Features
- TFT graphical interface with themes and brightness control.
- Scroll using `FN + ↑/↓`.
- Audio/screen notifications.
- Date/time from GPS/BT.
- *Path hash* adjustment.
- Real-time node/channel discovery.
- CAP LoRa-1262 support (based on `sosprz` fixes and UI inspired by `stachu`).

### Specifications

| Field | Value |
|---|---|
| Project | MCCC — MeshCore CardComm |
| Primary author | EA3IIU |
| Target device | M5Stack Cardputer ADV |
| Radio | CAP LoRa-1262 |
| Operation mode | Standalone / Bluetooth companion |
| Protocol | MeshCore / LoRa Mesh |
| Planned license | MIT |

### Credits
- Project created by **EA3IIU**.
- CAP LoRa-1262 support based on fixes by **sosprz**.
- UI approach inspired by **stachu**.

### Disclaimer
This is an experimental community project. It is not officially affiliated with M5Stack or MeshCore. It is not intended for emergency communications or safety-critical usage.
