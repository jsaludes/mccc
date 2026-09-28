# 📻 MCCC — MeshCore CardComm

[![Device](https://img.shields.io/badge/Device-M5Stack_Cardputer_ADV-orange.svg)](https://docs.m5stack.com/en/card/cardputer)
[![Hardware Module](https://img.shields.io/badge/LoRa-CAP_LoRa--1262-red.svg)](#-hardware--compatibilidad)
[![Callsign](https://img.shields.io/badge/Radioamateur-EA3IIU-blue.svg)](https://www.qrz.com/)
[![License](https://img.shields.io/badge/License-Planned_MIT-green.svg)](#-código-fuente--source-code)

Un cliente **MeshCore** standalone y companion diseñado específicamente para el **M5Stack Cardputer ADV**.

---

## 📝 Sobre el Proyecto / About

**Español**  
Tras probar distintos firmwares de MeshCore en el Cardputer ADV, detecté problemas de compatibilidad con repetidores locales y limitaciones de usabilidad diaria. Como radioaficionado (**EA3IIU**), decidí desarrollar **MCCC** con un objetivo claro: un dispositivo MeshCore 100% autónomo cuando no hay un smartphone cerca, pero capaz de funcionar como *Bluetooth Companion* cuando se requiere. 

*MCCC es ante todo un proyecto personal de aprendizaje y colaboración con la comunidad MeshCore.*

> **English Summary**  
> MCCC is a dedicated MeshCore client for the M5Stack Cardputer ADV + CAP LoRa-1262. Developed by radio amateur **EA3IIU**, it provides a fully standalone MeshCore experience while retaining Bluetooth companion mode for smartphones.

---

## 🛠️ Hardware & Compatibilidad

| Componente | Detalle / Modelo |
| :--- | :--- |
| **Dispositivo Principal** | M5Stack Cardputer ADV |
| **Módulo LoRa** | CAP LoRa-1262 |
| **Modos de Operación** | Standalone (Autónomo) / Bluetooth Companion |

---

## ✨ Características Principales / Features

- ✉️ **Mensajería Completa:** Muestra nombre de usuario, marca de tiempo (fecha/hora) e indicador de mensajes no leídos.
- 🔔 **Notificaciones Personalizables:** Alertas visuales y sonoras configurables para mensajes directos (DM) y canales.
- 🔍 **Búsqueda en Tiempo Real:** Filtro rápido de usuarios y canales integrados.
- ⌨️ **Navegación Cómoda:** Desplazamiento por el historial mediante `FN + ↑ / ↓`.
- ⚙️ **Compatibilidad MeshCore:** Configuración del tamaño del *path hash* para adaptarse a diversas redes locales.
- 🎨 **Personalización:** Temas de color de la interfaz y ajuste fino del brillo de pantalla.
- 🛰️ **GPS & Hora Automática:** Soporte para GPS físico y sincronización automática de hora al conectar con smartphone o GPS.
- 📶 **Dual Mode:** Funcionamiento completamente independiente o como *Bluetooth companion*.

---

## 💻 Código Fuente / Source Code

Por el momento, el código fuente de MCCC **no se encuentra disponible públicamente**. La intención es convertir el proyecto en open-source en una próxima versión y publicar el código bajo la **Licencia MIT**.

---

## 🙏 Créditos y Agradecimientos / Credits

MCCC es un proyecto independiente que se apoya en el trabajo de la comunidad:

* **MeshCore:** Basado en el firmware oficial de red MeshCore.
* **stachu:** Inspirado en la interfaz TFT de su firmware.
* **sosprz:** Correcciones de compatibilidad para la placa CAP LoRa-1262.

> *Nota: MCCC es un proyecto independiente y comunitario, no pretende sustituir ni representar oficialmente al proyecto MeshCore.*

---

## ⚠️ Disclaimer / Aviso Legal

> MCCC se proporciona como un proyecto comunitario y de desarrollo personal **"TAL CUAL" (AS IS)**, sin garantía de ningún tipo, expresa o implícita. El autor no será responsable de ninguna reclamación, daño u otra responsabilidad derivada de su uso. 
> 
> El uso de MCCC se realiza bajo la propia responsabilidad del usuario. El software puede contener errores o problemas de compatibilidad según el entorno de red LoRa o las versiones de MeshCore utilizadas.
