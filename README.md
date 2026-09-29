<img width="1688" height="932" alt="portada" src="https://github.com/user-attachments/assets/f597e18a-8120-4e59-b56f-ab028289cc0d" />

# 📻 MCCC — MeshCore CardComm

[![Device](https://img.shields.io/badge/Device-M5Stack_Cardputer-orange.svg)](https://docs.m5stack.com/en/card/cardputer)
[![Chipset](https://img.shields.io/badge/Chipset-ESP32--S3-blue.svg)](https://www.espressif.com/en/products/socs/esp32-s3)
[![License](https://img.shields.io/badge/License-Planned_MIT-green.svg)](#-source-code--código-fuente)
[![Buy Me A Coffee](https://img.shields.io/badge/Support-Buy_Me_A_Coffee-yellow.svg)](https://buymeacoffee.com/jsaludes)

ENGLISH
---

## 📝 About the Project

After trying out various MeshCore firmwares on the M5Stack Cardputer ADV, I encountered compatibility issues with my nearby repeaters running newer MeshCore versions, alongside some usability drawbacks for everyday use. As a developer and amateur radio operator (**EA3IIU**), I decided to develop my own client: **MCCC — MeshCore CardComm**.

My main goal was clear from the start: to make the Cardputer function as a fully independent MeshCore device without needing a phone nearby, while still retaining the ability to pair via Bluetooth as a companion whenever needed.

Above all, **MCCC is a personal learning project** focused on experimentation, solving real-world compatibility hurdles, and sharing progress with the MeshCore community.

---

## 🛠️ Hardware & Compatibility

| Component | Detail / Model |
| --- | --- |
| **Main Device** | M5Stack Cardputer ADV |
| **LoRa Transceiver** | CAP LoRa-1262 |
| **Operating Modes** | Standalone / Bluetooth Companion |

---

## ✨ Features

* ✉️ **Rich Messaging Display:** Shows username, timestamp (date & time), and unread message indicators.
* 🔔 **Configurable Alerts:** Customizable audio and visual notifications for direct messages (DMs) and channel traffic.
* 🔍 **Real-time Search:** Instant filtering for users and channels.
* ⌨️ **Ergonomic Navigation:** Smooth message and settings scrolling.
* ⚙️ **MeshCore Fine-Tuning:** Path hash size configuration to ensure maximum compatibility across different MeshCore network setups.
* 🎨 **UI Customization:** Color themes and fine display brightness control.
* 🛰️ **GPS & Clock Sync:** Physical GPS support and automatic RTC time sync upon connecting to a smartphone or GPS unit.
* 📶 **Dual Operation Mode:** Operates completely standalone or as a Bluetooth companion app interface.

---

## 💻 Source Code

* For the time being, the source code of MCCC is not publicly available. The goal is to transition the project to open source in an upcoming release under the **MIT License**.

---

## 🙏 Credits & Acknowledgments

MCCC is an independent community project that builds upon the great work of others:

* **MeshCore:** Based on the official MeshCore network protocol and firmware foundation.
* **stachu:** TFT interface design inspired by stachu's firmware interface.
* **sosprz:** CAP LoRa-1262 compatibility fixes based on work by sosprz.

> *Note: MCCC is an independent community development and is not officially affiliated with or endorsed by the core MeshCore project.*

---

## ⚠️ Disclaimer

> MCCC is provided as a community and personal development project on an **"AS IS"** basis, without warranty of any kind, express or implied. The author(s) shall not be held liable for any claim, damages, or other liability arising from or in connection with the software or its use.
> Use at your own risk. The software may contain bugs, compatibility issues, or unexpected behavior depending on network conditions, LoRa configurations, or MeshCore protocol updates.

---


SPANISH
---

## 📝 Sobre el Proyecto

Tras probar varios firmwares de MeshCore existentes en el M5Stack Cardputer ADV, me encontré con problemas de compatibilidad con mis repetidores próximos que ejecutan versiones más recientes de MeshCore, además de ciertos inconvenientes de usabilidad que no hacían cómodo el uso diario. Como desarrollador y radioaficionado (**EA3IIU**), decidí desarrollar mi propio cliente: **MCCC — MeshCore CardComm**.

Mi objetivo principal estuvo claro desde el principio: hacer que el Cardputer funcione como un dispositivo MeshCore completamente autónomo sin necesidad de llevar un teléfono cerca, manteniendo al mismo tiempo la capacidad de emparejarse por Bluetooth como *companion* cuando fuera necesario.

Por encima de todo, **MCCC es un proyecto de aprendizaje personal** enfocado en la experimentación, en resolver problemas de compatibilidad del mundo real y en compartir los progresos con la comunidad de MeshCore.

---

## 🛠️ Hardware y Compatibilidad

| Componente | Detalle / Modelo |
| --- | --- |
| **Dispositivo Principal** | M5Stack Cardputer ADV |
| **Módulo LoRa** | CAP LoRa-1262 |
| **Modos de Operación** | Autónomo (Standalone) / Compañero Bluetooth |

---

## ✨ Características

* ✉️ **Mensajería Completa:** Visualización del nombre de usuario, fecha/hora y un indicador de mensajes no leídos.
* 🔔 **Notificaciones Configurables:** Alertas sonoras y visuales personalizables para mensajes directos (DMs) y tráfico de canales.
* 🔍 **Búsqueda en Tiempo Real:** Filtrado instantáneo para usuarios y canales.
* ⌨️ **Navegación Ergonómica:** Desplazamiento fluido por los mensajes y ajustes.
* ⚙️ **Ajuste Fino de MeshCore:** Configuración del tamaño del *path hash* para garantizar la máxima compatibilidad en diferentes configuraciones de red MeshCore.
* 🎨 **Personalización de Interfaz:** Temas de color y control preciso del brillo de la pantalla.
* 🛰️ **GPS y Sincronización de Reloj:** Soporte físico para GPS y sincronización automática del RTC al conectar con un smartphone o unidad GPS.
* 📶 **Modo de Operación Dual:** Funciona de forma completamente independiente o como interfaz de aplicación auxiliar Bluetooth (*companion*).

---

## 💻 Código Fuente

* Por el momento, el código fuente de MCCC no se encuentra disponible públicamente. La intención es convertir el proyecto en código abierto en una próxima versión bajo la **Licencia MIT**.

---

## 🙏 Créditos y Agradecimientos

MCCC es un proyecto comunitario independiente que se apoya en el gran trabajo de otras personas:

* **MeshCore:** Basado en el protocolo de red oficial de MeshCore y su base de firmware.
* **stachu:** Diseño de la interfaz TFT inspirado en el interfaz de firmware de stachu.
* **sosprz:** Correcciones de compatibilidad para el CAP LoRa-1262 basadas en el trabajo de sosprz.

> *Nota: MCCC es un desarrollo comunitario independiente y no está afiliado oficialmente ni respaldado por el proyecto principal de MeshCore.*

---

## ⚠️ Aviso Legal (Disclaimer)

> MCCC se proporciona como un proyecto de desarrollo personal y comunitario "TAL CUAL" (*AS IS*), sin garantía de ningún tipo, ya sea expresa o implícita. Los autores no se hacen responsables de ninguna reclamación, daño u otra responsabilidad derivada de o en conexión con el software o su uso.
> Úsalo bajo tu propio riesgo. El software puede contener errores, problemas de compatibilidad o un comportamiento inesperado dependiendo de las condiciones de la red, las configuraciones de LoRa o las actualizaciones del protocolo MeshCore.
