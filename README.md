Fuente: https://www.incibe-cert.es/alerta-temprana/vulnerabilidades/cve-2018-20377

Vulnerabilidad en CVE-2018-20377 (CVE-2018-20377)
Tipo: Gestión de credenciales
Gravedad: Crítica
Fecha publicación : 23/12/2018
Última modificación: 28/12/2018
Descripción:Los dispositivos Orange Livebox 00.96.320S permiten que atacantes remotos descubran las credenciales wifi mediante /get_getnetworkconf.cgi en el puerto 8080, lo que conduce al control total si la contraseña del administrador es igual a la contraseña de la wifi o tiene el valor "admin" por defecto. Esto está relacionado con Firmware 01.11.2017-11:43:44, Boot v0.70.03, Modem 5.4.1.10.1.1A, Hardware 02 y Arcadyan ARV7519RW22-A-L T VR9 1.2.
Impacto
Vector de acceso: A través de red
Complejidad de Acceso: Baja
Autenticación: No requerida para explotarla
Tipo de impacto: Compromiso total de la integridad del sistema + Compromiso total de la confidencialidad del sistema + Compromiso total de la disponibilidad del sistema
Productos y versiones vulnerables

    Orange Arv7519rw22 Livebox 2.1 Firmware 00.96.321s
    Orange Arv7519rw22 Livebox 2.1 Firmware 00.96.217
    Orange Arv7519rw22 Livebox 2.1 Firmware 00.96.00.96.613
    Orange Arv7519rw22 Livebox 2.1 Firmware 00.96.00.96.609es

Referencias a soluciones, herramientas e información

    https://badpackets.net/over-19000-orange-livebox-adsl-modems-are-leaking-their-wifi-credentials/ (Origen: MISC)
    https://github.com/zadewg/LIVEBOX-0DAY (Origen: MISC)
    https://news.ycombinator.com/item?id=18745533 (Origen: MISC)
    https://web.archive.org/web/20181223120225/https://badpackets.net/over-19000-orange-livebox-adsl-modems-are-leaking-their-wifi-credentials/
