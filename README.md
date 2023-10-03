# INFORMATICA-UNIDAD-3

Unidad 3. Sistemas operativos
Definición e historia
Sistemas operativos libres y privativos
Funciones principales
Tareas y prácticas:
Tarea 3.1. Licenciamiento de software. (Entrega: 11 de septiembre).

Objetivo: Comprender los conceptos básicos de licenciamiento de software.

En equipo, investigue los conceptos básicos de licenciamiento de software: (1) propiedad intelectual en el caso del software, (2) patente de software, (3) dominio público (public domain), (4) distribución de software, (5) shareware, (6) freeware, (7) copyright vs copyleft, (8) licenciamiento de software (guía) y (9) software privativo (guía), (10) software abierto o de código abierto (open source) y revise la (11) Open Source Initiative (url) (guía), (12) software libre (free software), (13) la licencia GPL (url) y la Free Software Foundation (url) (guía).

Simplifique la definición con una frase corta y acompañe la definición con un par de ejemplos.

Vea el video Revolución de los Sistemas Operativos o The Code y tome sus notas. Finalmente, compare los tres tipos de software (privativo, abierto y libre) (guía), en términos de ventajas y desventajas y saque sus conclusiones filosóficas, técnicas, económicas, a partir de tres licencias representativas y de las biografías de tres personales: Bill Gates (Microsoft), Eric S. Raymond (OSI) y Richard Stallman (GNU - GLP) (guía). Reflexione sobre el software libre y abierto (FLOSS) como ideología y como negocio.

Documente en un video de hasta 10 minutos su experiencia en la realización de la actividad y comparta el video en el grupo de Telegram. Suba los archivos a su cuenta de Google Drive donde corresponda.

Práctica 3.2. Instalación de sistemas operativos en un medio extraible. (Demostrativa). ![image](https://github.com/EddyReyes01/informatica.1.1/assets/142960502/6baa7d24-c5cf-4161-be51-be1c11264c47)


Objetivo: Aprender a usar varios sistemas operativos desde un medio extraíble.

Parte 1. Investigue qué es un sistema operativo (guía), tipos de sistemas operativos (guía) y compárelos en términos de ventajas, desventajas, seguridad, usabilidad y robustez (url).

Parte 2. Investigue qué es una imagen ISO y cómo se usa. Utilice Qbittorrent y, mediante su motor de búsqueda, localice la imagen ISO del sistema operativo Windows 7, usando la frase "Windows 7 untouched genuine" o "Windows 7 Ultimate spanish" (tutorial) o busque el torrent aquí. Identifique la entrada que tiene más semillas (seeds) y descárguela.

Parte 3. Investigue un poco sobre las distribuciones del sistema operativo GNU/Linux (guía). Descargue el archivo ISO del sistema operativo Linux Fedora (guía) o Zorin OS de 32 o 64 bits, según sea la arquitectura del procesador (CPU) de su computadora (x86_64, por lo general).

Parte 4. Esta parte de la práctica requiere un dispositivo externo (USB o disco duro externo).

Advertencia: Siempre debe tener cuidado de NO instalar Ventoy, Yumi o Rufus en el disco duro de su computadora. Por ello, previamente, siempre debe respaldar los archivos de la USB. Después de preparar la USB, ya puede utilizarla para grabar otros archivos en ella.

En una USB con capacidad mayor al archivo ISO que usará (mayor a 4 GiB) instale el programa para crear el USB live que le permitirá arrancar el sistema operativo a instalar, con alguna de las siguientes aplicaciones:

Rufus (tutorial en video, guía escrita. Rufus sólo instala una imagen ISO, a la vez.
Fedora Media Writer (tutorial). Fedora Media Writer sólo instala una imagen ISO, a la vez.
Ventoy** (tutorial en video, tutorial escrito). Ventoy es multiboot, por lo que una vez preparada la USB, sólo copie el o los archivos ISO a la raíz y listo! Nota: Para arrancar la ISO de Windows, descargue el archivo que debe ponerlo en la raíz de la USB.
Yumi (guía en video, tutorial escrito). Yumi es multiboot por lo que, cada vez que ejecute Yumi, puede instalar o desinstalar las imágenes ISO de los sistemas operativos que desee.
Considere de manera alternativa que el sistema operativo Windows puede instalarse en un medio extraible con WintoUSB siguiendo este tutorial, pero requiere una licencia activa.

Cualquiera de los procedimientos de esta Parte 4, habilitan una USB para arrancar cualquier sistema operativo (Windows, Linux u otro) sin tocar el disco duro del equipo. También puede utilizarlo para instalar el sistema operativo en el mismo disco duro, adicional a Windows (dual booting) o instalarlo otra USB. Esto tiene muchas aplicaciones prácticas, por ejemplo, si falla el sistema operativo Windows, con la USB que ha preparado puede arrancar su sistema operativo Linux desde la USB y trabajar con él en tareas cotidianas de oficina como abrir o crear un archivo de texto u hoja de cálculo con Libre Office, navegar en Internet y acceder a su correo electrónico. Sin embargo, no puede hacer cambios al sistema operativo, ni instalar aplicaciones adicionales con cambios permanentes, pero esto será posible si lo instala en otra USB, de manera permanente.

Parte 5. Investigue los conceptos involucrados: bootear un equipo (guía), BIOS (guía), UEFI (guía), partición (física y lógica, de arranque) (guía), GPT y MBR (guía).

Pruebe que puede arrancar (o bootear) live USB del sistema operativo desde la USB:

Active Boot Disk
Windows 7
Fedora Workstation.
Parte 6. Para instalar el sistema operativo Linux en otra USB, de manera permanente y usarlo alternativamente desde su USB, conservando los cambios que haga en él, utilice el siguiente procedimiento. Ejecute la parte 4 y 5. Una vez arrancado el USB Live puede utilizar un disco duro externo de baja capacidad vacío o una memoria USB vacía de por lo menos 64 GB. Por ejemplo, el sistema operativo Linux Fedora* según el siguiente tutorial.

Documente en un video su experiencia en la realización de la actividad en cada parte y comparta los videos en el grupo de Telegram. Suba los archivos a su cuenta de Google Drive donde corresponda.

Práctica 3.3. Instalación de sistemas operativos como máquinas virtuales. (Entrega: 13 de septiembre). 

Objetivo: Aprender a instalar varios sistemas operativos como un máquinas virtuales.

Parte 1. Investigue qué es la virtualización, una máquina virtual y cómo se instala un sistema operativo en una máquina virtual. ![image](https://github.com/EddyReyes01/informatica.1.1/assets/142960502/4da861ed-ee3e-4137-bb60-e9ea994070ff)


Parte 2. Instale VirtualBox en su sistema operativo Windows o el que tenga. Luego, instale el sistema operativo Fedora Workstation como una máquina virtual (Video 1). Finalmente, instale el VirtualBox Extension Pack.x

Parte 3. Utilice los archivos ISO de Windows 7 y Fedora Workstation e instálelos mediante VirtualBox (Video).

Parte 4. Pruebe que puede arrancar cada uno de los dos sistemas operativos como máquinas virtuales.

Documente en un video su experiencia en la realización de la actividad en cada parte y comparta los videos en el grupo de Telegram. Suba los archivos a su cuenta de Google Drive donde corresponda.

Práctica 3.4. Particiones y sistemas de archivos. (Entrega: 18 de septiembre).

Objetivo: Comprender y practicar la preparación de dispositivos de almacenamiento en una computadora.

Parte 1. Investigue los conceptos involucrados: partición (física y lógica, primaria, partición de arranque) (guía), GPT y MBR (guía), formatear un dispositivo de almacenamiento (guía), sistema de archivos (guía), archivo (guía), tipos de archivo (binario, texto, programa) (guía), cómo se guarda un archivo (guía) y las operaciones de manejo de archivos (guía).

Parte 2. Use una USB sin datos o nueva y practique los procesos de manejo de particiones (crear, cambiar de tamaño, fusionar y eliminar particiones en Windows con Disk Management (guía), de los siguientes tipos: FAT, exFAT, FAT32, NTFS y EXT4. Saque sus conclusiones.

Parte 3. Repita las mismas operaciones de la Parte 3 de esta práctica usando la aplicación GParted Live CD/USB/HD/PXE Bootable Image copiando el archivo ISO en la USB con Ventoy y arrancando el ISO. Utilice este tutorial. Compare Disk Management y gParted y saque sus conclusiones.

Parte 4. Practique la recuperación de particiones eliminadas con TestDisk (tutorial en video, tutorial escrito) en discos o dispositivos de almacenamiento formateados. También, practique la recuperación de dispositivos que no son reconocidos o que piden ser formateados, como una USB (tutorial).

Aplicación: Con alguna de estas dos herramientas se puede preparar el disco duro de la computadora para instalar Linux como segundo sistema operativo o en dual boot, sin perder información, después de dejar un espacio libre de unos 20 a 50 GB, dependiendo del tamaño del disco disponible. Ver este tutorial.

Desarrolle la actividad en su cuaderno y, luego, documente cada parte en un video de hasta 10 minutos su experiencia en la realización de la actividad y comparta el video en el grupo de Telegram. Suba los archivos a su cuenta de Google Drive donde corresponda.

Desarrolle la actividad en su cuaderno y, luego, documente cada parte en un video de hasta 10 minutos su experiencia en la realización de la actividad y comparta el video en el grupo de Telegram. Suba los archivos a su cuenta de Google Drive donde corresponda.

Práctica 3.5. Particiones y sistemas de archivos. (Entrega: 20).

Objetivo: Comprender y practicar la preparación de dispositivos de almacenamiento en una computadora.

Parte 1. Investigue los conceptos involucrados: partición (física y lógica, primaria, partición de arranque) (guía), GPT y MBR (guía), formatear un dispositivo de almacenamiento (guía), sistema de archivos (guía), archivo (guía), tipos de archivo (binario, texto, programa) (guía), cómo se guarda un archivo (guía) y las operaciones de manejo de archivos (guía).

Parte 2. Use una USB sin datos o nueva y practique los procesos de manejo de particiones (crear, cambiar de tamaño, fusionar y eliminar particiones en Windows con Disk Management (guía), de los siguientes tipos: FAT, exFAT, FAT32, NTFS y EXT4. Saque sus conclusiones.

Parte 3. Repita las mismas operaciones de la Parte 3 de esta práctica usando la aplicación GParted Live CD/USB/HD/PXE Bootable Image copiando el archivo ISO en la USB con Ventoy y arrancando el ISO. Utilice este tutorial. Compare Disk Management y gParted y saque sus conclusiones.

Parte 4. Practique la recuperación de particiones eliminadas con TestDisk (tutorial en video, tutorial escrito) en discos o dispositivos de almacenamiento formateados. También, practique la recuperación de dispositivos que no son reconocidos o que piden ser formateados, como una USB (tutorial).

Aplicación: Con alguna de estas dos herramientas se puede preparar el disco duro de la computadora para instalar Linux como segundo sistema operativo o en dual boot, sin perder información, después de dejar un espacio libre de unos 20 a 50 GB, dependiendo del tamaño del disco disponible. Ver este tutorial.

Desarrolle la actividad en su cuaderno y, luego, documente cada parte en un video de hasta 10 minutos su experiencia en la realización de la actividad y comparta el video en el grupo de Telegram. Suba los archivos a su cuenta de Google Drive donde corresponda.
