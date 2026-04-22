# MacCaffeinate
Comandos Caffeinate Mac
------
Para mantener tu Mac despierta indefinidamente (ideal para que Hermes no se duerma):

caffeinate -d -i -m -u
Qué hace cada flag:
-d → evita que se apague la pantalla
-i → evita que el sistema entre en reposo
-m → evita que los discos se duerman
-u → simula actividad del usuario

👉 Básicamente: tu Mac nunca se duerme mientras ese proceso esté corriendo
--------

Si quieres dejarlo corriendo en segundo plano:
caffeinate -d -i -m -u &
---------
Para detenerlo:
killall caffeinate
