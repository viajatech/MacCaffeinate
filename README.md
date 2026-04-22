# MacCaffeinate
Comandos Caffeinate Mac
------
Para mantener tu Mac despierta indefinidamente (ideal para que Hermes no se duerma):

caffeinate -d -i -m -u
--------
Qué hace cada flag:
-d → evita que se apague la pantalla
-i → evita que el sistema entre en reposo
-m → evita que los discos se duerman
-u → simula actividad del usuario

👉 Básicamente: tu Mac nunca se duerme mientras ese proceso esté corriendo
--------

Si quieres dejarlo corriendo en segundo plano:
--------
caffeinate -d -i -m -u &
---------
Para detenerlo:
-------
killall caffeinate
--------
🔎 1. Ver si el proceso está activo

En la terminal:
-----

ps aux | grep caffeinate
----

Si ves algo como esto:

david   12345   0.0  caffeinate -d -i -m -u
----

👉 listo, sí está funcionando
