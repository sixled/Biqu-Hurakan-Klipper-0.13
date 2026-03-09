👁️ Sauron.3d  - Klipper v0.13 Custom ROM

ROM personalizada para Biqu Hurakan. Plug & Play, sin errores de pantalla y optimizada para la comunidad.
✨ Características Principales

    LCD "Black Screen" Fix: Corrección del código fuente para que la pantalla encienda siempre.

    KIAUH Ready: Actualizaciones fáciles de todo el ecosistema Klipper.

    Optimizada para BMG: Configuración de extrusor lista para el upgrade.

⚠️ ¡IMPORTANTE! Antes de Empezar

Hacé una copia de seguridad de tu archivo printer.cfg actual.
⚙️ Configuración del Extrusor

Esta ROM viene configurada por defecto para un extrusor BMG.

Si tenés el extrusor original (Stock) o perdiste tu backup:

    Entrá a la interfaz web (Mainsail/Fluidd).

    Debés BORRAR completamente la sección de [extruder].

    Asegurate de configurar z_offset = 2.0 en tu nueva configuración y calibrar antes de imprimir para evitar daños en la cama.

🚀 Instalación Paso a Paso
1. Flash MCU (Placa Base)

    Copiá el archivo firmware.bin en una microSD (formateada en FAT32).

    Con la impresora apagada, quitá la tarjeta de la ranura "SD CARD" (sistema).

    Insertá la tarjeta con el firmware en la ranura de la placa MCU y encendé la impresora.

    Cuando el LCD encienda y diga "Hurakan v1", el proceso habrá terminado.

2. Flash SD (Sistema Operativo)

    Bajá el archivo .img.xz desde la sección Releases.

    Graba la imagen con BalenaEtcher o Raspberry Pi Imager en la SD de la impresora.

    Insertala en la ranura SD CARD y encendé la impresora.

3. Configuración Final

    Entrá a la interfaz web y reemplazá el printer.cfg genérico por el tuyo.

🎨 Personalización del Fondo (Mainsail)

Para cambiar el fondo de la interfaz web:

    Entrá a la sección Machine en el menú lateral.

    Abrí la carpeta llamada Backgrounds.

    Subí tu imagen (⚠️ Solo formato .jpg).

📸 Comunidad y Soporte

    Instagram: @Sauron.3d

    Reportes: Si encontrás un error, abrí un "Issue" aquí en GitHub.

    Aviso: Verificá siempre que tu hardware esté en condiciones antes del flasheo.
