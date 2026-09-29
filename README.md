<img width="1688" height="932" alt="portada" src="https://github.com/user-attachments/assets/a7e489e6-0611-4634-82be-dac5115797c3" />
# 📻 MCCC — MeshCore CardComm

[![Device](https://img.shields.io/badge/Device-M5Stack_Cardputer_ADV-orange.svg)](https://docs.m5stack.com/en/card/cardputer)
[![Hardware Module](https://img.shields.io/badge/LoRa-CAP_LoRa--1262-red.svg)](#-hardware--compatibility)
[![Callsign](https://img.shields.io/badge/Radioamateur-EA3IIU-blue.svg)](https://www.qrz.com/)
[![License](https://img.shields.io/badge/License-Planned_MIT-green.svg)](#-source-code)

A standalone and Bluetooth companion **MeshCore** client built specifically for the **M5Stack Cardputer ADV**.

---

## 📝 About the Project

### English
After trying out various MeshCore firmwares on the M5Stack Cardputer ADV, I encountered compatibility issues with my local repeaters running newer MeshCore versions, alongside some usability drawbacks for everyday use. As an active amateur radio operator (**EA3IIU**), I decided to develop my own client: **MCCC — MeshCore CardComm**.

My main goal was clear from the start: to make the Cardputer function as a fully independent MeshCore device without needing a phone nearby, while still retaining the ability to pair via Bluetooth as a companion whenever needed. 

Above all, **MCCC is a personal learning project** focused on experimentation, solving real-world compatibility hurdles, and sharing progress with the MeshCore community.

> **Resumen en Español**  
> MCCC es un cliente MeshCore desarrollado por el radioaficionado **EA3IIU** para el M5Stack Cardputer ADV + CAP LoRa-1262. Nació para solucionar problemas de compatibilidad con repetidores locales y ofrecer una experiencia 100% autónoma (*standalone*), permitiendo al mismo tiempo su uso como *Bluetooth companion* para el smartphone.

---

## 🛠️ Hardware & Compatibility

| Component | Detail / Model |
| :--- | :--- |
| **Main Device** | M5Stack Cardputer ADV |
| **LoRa Transceiver** | CAP LoRa-1262 |
| **Operating Modes** | Standalone / Bluetooth Companion |

---

## ✨ Features

- ✉️ **Rich Messaging Display:** Shows username, timestamp (date & time), and unread message indicators.
- 🔔 **Configurable Alerts:** Customizable audio and visual notifications for direct messages (DMs) and channel traffic.
- 🔍 **Real-time Search:** Instant filtering for users and channels.
- ⌨️ **Ergonomic Navigation:** Smooth message scrolling using `FN + ↑ / ↓`.
- ⚙️ **MeshCore Fine-Tuning:** Path hash size configuration to ensure maximum compatibility across different MeshCore network setups.
- 🎨 **UI Customization:** Color themes and fine display brightness control.
- 🛰️ **GPS & Clock Sync:** Physical GPS support and automatic RTC time sync upon connecting to a smartphone or GPS unit.
- 📶 **Dual Operation Mode:** Operates completely standalone or as a Bluetooth companion app interface.

<details>
<summary><b>🇪🇸 Ver características en español</b></summary>

- ✉️ **Mensajería Completa:** Nombre de usuario, fecha/hora e indicador de mensajes no leídos.
- 🔔 **Notificaciones Configurables:** Alertas sonoras y visuales para DMs y canales.
- 🔍 **Búsqueda en Tiempo Real:** Filtro rápido de nodos y canales.
- ⌨️ **Navegación:** Desplazamiento por mensajes mediante `FN + ↑ / ↓`.
- ⚙️ **Ajuste de Path Hash:** Máxima compatibilidad con diferentes redes MeshCore.
- 🎨 **Personalización:** Temas de color y ajuste de brillo de pantalla.
- 🛰️ **GPS y Hora:** Sincronización automática de hora mediante smartphone o módulo GPS.
- 📶 **Modo Dual:** Funciona de forma 100% independiente o mediante Bluetooth companion.
</details>

---

## 💻 Source Code

- **English:** For the time being, the source code of MCCC is not publicly available. The goal is to transition the project to open source in an upcoming release under the **MIT License**.
- **Español:** Por el momento, el código fuente no se encuentra disponible públicamente. La intención es convertir el proyecto en código abierto en una próxima versión bajo la **Licencia MIT**.

---

## 🙏 Credits & Acknowledgments

MCCC is an independent community project that builds upon the great work of others:

- **MeshCore:** Based on the official MeshCore network protocol and firmware foundation.
- **stachu:** TFT interface design inspired by stachu's firmware interface.
- **sosprz:** CAP LoRa-1262 compatibility fixes based on work by sosprz.

> *Note: MCCC is an independent community development and is not officially affiliated with or endorsed by the core MeshCore project.*

---

## ⚠️ Disclaimer

> MCCC is provided as a community and personal development project on an **"AS IS"** basis, without warranty of any kind, express or implied. The author(s) shall not be held liable for any claim, damages, or other liability arising from or in connection with the software or its use. 
> 
> Use at your own risk. The software may contain bugs, compatibility issues, or unexpected behavior depending on network conditions, LoRa configurations, or MeshCore protocol updates.


Quiero este readme en ingles y en español, de modo que se muestre la misma información en los dos idiomas, no resumenes
