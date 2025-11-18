# Tema 7
# Sincronizar varios hilos
# 1.Conceptos teoricos. Desarrollar cada concepto brebemente

## 1.1. Capas del modelo OSI. Explicalos brevemente 

La estandarización del modelo OSI dicta cómo deben funcionar las comunicaciones entre redes

Se divide en 7 capas:
* Capa física: se encarga de la transmisión física de datos a través del medio de transmisión, como cables, fibra óptica o señales inalámbricas.
* Capa de enlace de datos: comunicación fiable y sin errores entre dos dispositivos en la misma red local.
* Capa de red: Esta capa enrutará (ruta más óptima las redes). Su objetivo principal es hacer que los datos lleguen desde su origen
a su destino.
* Capa de transporte: transporte de datos fiable y orientado a la conexión entre dos dispositivos que pueden estar en redes diferentes
* Capa de sesión: establece, administra y termina las sesiones de comunicación entre dos dispositivos.
* Capa de presentación: esta capa se encarga de la representación de datos y la traducción entre formatos de datos.
* Capa de aplicación: es la capa superior y se relaciona directamente con las aplicaciones y servicios de usuario final.

## 1.2. Capas del modelo TCP/IP. Explicalos brevemente

EL protocolo TCP/IP consta de las siguientes capas:
* Capa de aplicación: compuesta por aplicaciones red
* HTTP: comunica servers con navegadores web
* SMTP: gestiona el correo electrónico
* DNS: traduce a direcciones IP los dispositivos de la red
* FTP: transferencia de ficheros
* NFS: compartir ficheros en diferentes ordenadores de una red
* TELNET: conexión remota de terminales
* Capa de transporte: proporcionar servicios de transporte de datos, entre dispositivos en diferentes redes.
* Capa de Internet: elementos software que dirigen los paquetes por la red
* Capa de red: elementos hardware de comunicaciones, tarjetas red, cables…

### 1.3 ¿Cuales son las diferencias entre los modelos OSCI y TCP/IP?

El modelo OSI es más completo y teórico, mientras que el modelo TCP/IP es más simple y se ajusta mejor a la realidad de las redes de Internet. 

Ambos modelos son útiles en diferentes contextos. Ejemplo de usos:
* Modelo OSI: planificación de redes a gran escala, proyectos de investigación, enseñanza…
* Modelo TCP/IP: redes pequeñas y menos complejas como empresariales y domésticas, administrar sistemas…

