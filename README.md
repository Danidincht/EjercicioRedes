# EjercicioRedes
Crear cinco redes:

Crear tres subredes (VLSM), una que soporte 100 host, otra que soporte 30 y por último una para 6 host. Sólo esta última podrá salir fuera. Cada una tendrá cuatro ordenadores conectados.
8 ordenadores con DHCP.
4 ordenadores con DHCP.
4 ordenadores con IP fija, un punto de enlace con 5 ordenadores con DHCP.
5 ordenadores con IP fija.

Las subredes estarán compuestas en los siguientes rangos: 192.168.1.1/25 - 192.168.1.126/25, 192.168.1.128/27 - 192.168.1.159/27, 192.168.1.161/29 - 192.168.1.168/29

La segunda red usará la red 192.168.2.0, y usará un servidor DHCP en la ip 192.168.2.2 que dará ip a los dispositivos de la red.

La tercera red usará la red 192.168.3.0 y usará otro servidor DHCP en la ip 192.168.3.2.

La cuarta red usará la red 192.168.5.0 y cuenta con 5 ordenadores conectados a un servidor DHCP en la ip 192.168.5.2 y con 4 ordenadores en el rango de ips 192.168.5.8 - 192.168.5.12

La quinta red usará la red 192.168.4.0 y tiene 5 ordenadores con ips fijas.


Todas las redes estarán conectadas mediante routers.
Cada router tiene la primera ip de su red y, además, se conectan entre si usando las redes 192.168.10.0 hasta 192.168.13.0.

Tendremos tres servidores web
Los servidores web se encuentran en la quinta red y cada uno de ellos cuenta con su propia ip fija.

Existirá un servidor DNS para resolver los nombres anteriores.
El servidor DNS se encuentra en la quinta red , además de tener su ip fija, almacena los nombres de los servidores web la red.

Cada una de las redes se encuentra etiquetada con su ip de red.
