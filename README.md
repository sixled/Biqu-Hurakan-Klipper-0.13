# 👁️ Sauron.3d  - Klipper v0.13 Custom ROM

![Version](https://img.shields.io/badge/Version-v0.13.0-orange?style=for-the-badge)
![Hardware](https://img.shields.io/badge/Hardware-Biqu_Hurakan_%7C_Manta_M4P-blue?style=for-the-badge)

ROM personalizada para **Biqu Hurakan**. Plug & Play, sin errores de pantalla y optimizada para la comunidad.

## ✨ Características Principales
* **LCD "Black Screen" Fix:** Corrección del código fuente para que la pantalla encienda siempre.
* **KIAUH Ready:** Actualizaciones fáciles de todo el ecosistema Klipper.
* **Optimizada para BMG:** Configuración de extrusor lista para el upgrade.

---
*********Hace una copia del printer.cfg*********
## ⚙️ Configuración del Extrusor (¡IMPORTANTE!)
Esta ROM viene configurada por defecto para un extrusor **BMG**. 

⚠️ **Si tenés el extrusor original (Stock):**
Debés entrar a tu `printer.cfg`, **BORRAR** completamente la sección de `[extruder]`.

---

## 🎨 Personalización del Fondo (Mainsail)
Para cambiar el fondo de la interfaz web:
1. Entrá a la sección **Machine** en el menú lateral.
2. Abrí la carpeta llamada `Backgrounds`.
3. Subí tu imagen (⚠️ **Solo formato .jpg**).

---
## 🌐 Gestión de Red (IP Address)
Para facilitar la conexión, he añadido una sección específica en la interfaz:
* Andá al menú lateral y buscá la carpeta **Network**.
* Ahí podrás visualizar la **IP actual** de tu impresora para acceder desde cualquier navegador en tu red local.

---
## 🚀 Instalación
1. **Descarga:** Bajá los archivos desde la sección [Releases](https://github.com/sixled/Biqu-Hurakan-Klipper-0.13/releases).
2. **Flash SD:** Grabá el `.img.xz` con BalenaEtcher en una SD de 32GB para la CB1.
3. **Flash MCU:** Copiá el `firmware.bin` en una microSD (FAT32), insertala en la placa base y encendé la impresora para activar el LCD.

---

## 📸 Comunidad y Soporte
* **Instagram:** [@Sauron.3d](https://www.instagram.com/Sauron.3d)
* **Reportes:** Si encontrás un error, abrí un "Issue" aquí en GitHub.

> **Aviso:** Verificá siempre que tu impresora ande bien antes del flasheo.
