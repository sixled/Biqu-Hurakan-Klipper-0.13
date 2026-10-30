👁️ Sauron.3d  - Klipper v0.13.8 hurakanv2 Debian 13 Custom ROM

ROM biqu  personalizada para Biqu Hurakan. Plug & Play, sin errores de pantalla y optimizada para la comunidad.
✨ Características Principales

    LCD "Black Screen" Fix: Corrección del código fuente para que la pantalla encienda siempre.

    KIAUH Ready: Actualizaciones fáciles de todo el ecosistema Klipper.
    sonor :Para tener una red WIFI potente sin caida .
    timelapse- para grabar tu impresion3d  si tenes camara 
    fondo -  PARA tener tu fondo personalizado.
    Version: v0.13.0-818-g020d25e7-dirty 


⚠️ ¡IMPORTANTE! Antes de Empezar

Hace una copia de seguridad de tu archivo printer.cfg actual.

Si  perdiste tu backup:

    luego de actualizar Entrá a la interfaz web (Mainsail/Fluidd).
    Hacer Home y calibra la cama
    Coloca en la consola PROBE_CALIBRATE y configura tu z-offset
    calibrar antes de imprimir para evitar daños en la cama.

🚀 Instalación Paso a Paso
1. Flash MCU (Placa Base)

    Copia el archivo firmware.bin en una microSD (formateada en FAT32).

    Con la impresora apagada, quita la tarjeta de la ranura "SD CARD" (sistema).

    Inserta la tarjeta con el firmware en la ranura de la placa MCU y encendé la impresora.

    Cuando el LCD encienda y diga "muestre el logo de biqu ", el proceso habrá terminado.

2. Flash SD (Sistema Operativo)

    Bajá el archivo .img.xz desde la sección Releases.

    Graba la imagen con Raspberry Pi Imager de  la SD de la impresora.

    Insertala en la ranura SD CARD y encendé la impresora.

3. Configuración Final

    Entra a la interfaz web y reemplaza el printer.cfg genérico por el tuyo.
   Ademas debes de agregarle al principio de todo [Include base/hurakanv2.cfg] Agregaras muchas funciones necesarias para que te ande.
   incluyendo un diagnosticador del sensor de calibración de cama.

🎨 Personalización del Fondo (Mainsail)

Para cambiar el fondo de la interfaz web:

    Entrá a la sección Machine en el menú lateral.

    Abrí la carpeta llamada  wallapepers.

    Subí tu imagen  se debe llamar home.png luego mantene apretado la tecla Control + F5 para ver el cambio

    
Configuracion Red Wifi :  
Opcion 1 -  Instala la app android y luego enciende el hotspot de la impresora  espera 1minuto luego abre la app y selecciona instala la impresora.  Coloca tus credenciales de la red y deja que la app lo configure .

**Para usar el hotspot ve al menu conectividad y activa el hospot .  
La impresora solo puede usar la red wifi o el  hostpot a la vez  no todo junto.
la contraseña del hotspot es hurakanv2

Opcion 2 -** Conecta tu microSD  con el adaptador a la pc  y Modifica el archivo llamado  system.cfg en donde dice WIFI-SSID y PASSW  (***NO formatees la microsd **** )prende la impresora 3d y coloca la microSD  luego en el menú Network veras la ip .

*El diagnostigador de Microprobe analiza si tiene alguna falla al retraer o desplegar ademas también te dice que versión es tu Microprobe.


📸 Comunidad y Soporte

    Instagram: @Sauron.3d

    Reportes: Si encontrás un error, abrí un "Issue" aquí en GitHub.
