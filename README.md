#73Linux
## Descripción

73 Linux es la siguiente evolución de Build a Pi. No solo 73 Linux soporta Raspberry Pi,
sino que también es compatible con sistemas x86_64 basados en Debian. Ahora puedes usar
un notebook con Ubuntu o Mint con la misma facilidad que antes en la Pi. Siguiendo las
tradiciones de Build a Pi, tienes **CONTROL TOTAL** sobre la construcción del sistema, a
diferencia de las imágenes preconstruidas. Esto te permite elegir qué aplicaciones
quieres instalar y omitir las que no necesitas, manteniendo tu sistema lo más liviano y
eficiente posible.

Otra gran característica es la capacidad de hacer “side load” de nuevas aplicaciones.
Cualquiera puede crear un archivo bapp y colocarlo en el directorio de la comunidad, y
el sistema de menús de 73 Linux lo cargará automáticamente junto con las aplicaciones
principales.

Un pequeño ejemplo de un archivo bapp personalizado sería cuando tu organización utiliza
un formulario Winlink personalizado o un formulario FLMSG propio. Algún usuario con buen
manejo de Linux dentro de tu grupo podría crear un archivo bapp personalizado para ayudar
al resto de la organización a asegurarse de que los formularios se instalen en el
directorio correcto.

Los usuarios finales siguen teniendo control total sobre los archivos personalizados y
pueden elegir mostrar o ignorar archivos bapp que no estén incluidos en el paquete oficial
de 73 Linux.

# Compatibilidad

Hasta ahora, 73 Linux ha sido probado en la Pi 4 ejecutando Pi OS de 32 bits y en el
notebook Evolve Maestro.

Puedes ejecutar 73 Linux directamente sobre una instalación antigua de Build a Pi.
~~73 Linux eliminará cualquier instalación previa de BAP durante la ejecución inicial.~~
Próximamente.

# Instalación

**Nota:** VARA puede no instalarse en la primera ejecución. Si eso ocurre, ejecuta 73 Linux
nuevamente y selecciona VARA en la segunda pasada.

La instalación sigue siendo muy sencilla. Solo ejecuta el siguiente comando:

     git clone https://github.com/km4ack/73Linux.git $HOME/73Linux && bash $HOME/73Linux/73.sh

Si el comando anterior falla, es posible que no tengas git instalado. En ese caso, ejecuta:

     sudo apt install git

y luego vuelve a ejecutar el comando git clone.

# Reporte de problemas y solicitudes de nuevas funciones

https://github.com/km4ack/73Linux/issues

# ¡Más documentación próximamente!

# Créditos

Un gran agradecimiento a Kelly Keaton por su enorme contribución al nuevo sistema de
menús, a los Patrons por su tiempo probando versiones tempranas, y a todos quienes han
reportado errores a lo largo de los años. Cada uno de ustedes ha ayudado a que este
proyecto sea lo que es hoy. Otros colaboradores de código incluyen:

jangliss  
Jehreg  
Rescue9  
hsmalley  
chrisBosse  
kuperman  
NullVibes
