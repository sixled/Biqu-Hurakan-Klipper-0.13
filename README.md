👁️ Sauron.3d  - Klipper v0.13.6 hurakanv2 Debian 13 Custom ROM

ROM personalizada para Biqu Hurakan. Plug & Play, sin errores de pantalla y optimizada para la comunidad.
✨ Características Principales

    LCD "Black Screen" Fix: Corrección del código fuente para que la pantalla encienda siempre.

    KIAUH Ready: Actualizaciones fáciles de todo el ecosistema Klipper.


⚠️ ¡IMPORTANTE! Antes de Empezar

Hacé una copia de seguridad de tu archivo printer.cfg actual.
⚙️ Configuración del Extrusor

Esta ROM viene configurada por defecto para un extrusor BMG.

Si  perdiste tu backup:

    luego de actualizar Entrá a la interfaz web (Mainsail/Fluidd).
    Hacer Home y calibra la cama
    Coloca en la consola PROBE_CALIBRATE y configura tu z-offset
    calibrar antes de imprimir para evitar daños en la cama.

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
   Ademas debes de agregarle al principio de todo [Include base/hurakanv2.cfg] Agregaras muchas funciones necesarias para que te ande.
   incluyendo un diagnostigador del sensor de calibracion de cama.

🎨 Personalización del Fondo (Mainsail)

Para cambiar el fondo de la interfaz web:

    Entrá a la sección Machine en el menú lateral.

    Abrí la carpeta llamada wallapepers.

    Subí tu imagen (⚠️ Solo formato .jpg). se debe llamar fondo.jpg luego mantene apretado la tecla Control + F5 para ver el cambio

    
Configuracion Red Wifi :  Conecta tu microSD  con el adaptador a la pc  y Modifica el archivo llamado  wifi.conf  (NO formatees la microsd )prende la impresora 3d. Cuando escuches un pitido es porque ya te tomo los cambios y puedes ver tu ip en el menu Network.
(Hostpot) Muy pronto subire una app para que puedas configurar la red wifi sin sacar la microSd de la impresra.
*El diagnostigador de Microprobe analiza si tiene alguna falla al retraer o desplegar ademas tambien te dice que version es tu microprobe.


📸 Comunidad y Soporte

    Instagram: @Sauron.3d

    Reportes: Si encontrás un error, abrí un "Issue" aquí en GitHub.
