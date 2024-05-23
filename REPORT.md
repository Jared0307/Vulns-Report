Informe de Escaneo de Red
Introducción

Este informe detalla los resultados de un escaneo de red realizado en una red local específica. El objetivo del escaneo fue identificar los dispositivos activos en la red y analizar los servicios y puertos abiertos en esos dispositivos.
Escaneo de Dispositivos Activos
![captura_000](https://github.com/Jared0307/Home-s-vulns-report/assets/101056540/5ff59785-f20d-4ac5-a7d7-f9c74a0604d1)

Se realizó un escaneo inicial de dispositivos activos en la red utilizando la herramienta Nmap. A continuación se muestra un resumen de los dispositivos identificados:

    192.168.100.1 (Router o Punto de Acceso)
    192.168.100.2 (Caja de Totalplay)
    192.168.100.8
    192.168.100.9
    192.168.100.15
    192.168.100.16 (Computadora Windows)
    192.168.100.23
    192.168.100.26 (Pantalla LG)

Análisis de Servicios y Puertos Abiertos

Después de identificar los dispositivos activos, se realizó un escaneo detallado de los puertos abiertos en los dispositivos clave. 
![captura](https://github.com/Jared0307/Home-s-vulns-report/assets/101056540/c3c5d656-0ebd-40af-92c6-f415868dbb24)

A continuación se presentan las observaciones sobre los servicios y puertos abiertos en cada dispositivo relevante:
192.168.100.2 (Caja de Totalplay)

    Servicios abiertos: HTTP (puerto 80), Sun Answerbook (puerto 8888), y dos puertos desconocidos (9431/tcp, 56789/tcp).
    Sistema operativo: Sagemcom Broadband SAS

192.168.100.16 (Computadora Windows)

    Servicios abiertos: HTTP (puerto 80), msrpc (puerto 135), netbios-ssn (puerto 139), microsoft-ds (puerto 445), y otros puertos desconocidos.
    Sistema operativo: Liteon Technology

192.168.100.23

    Servicios abiertos: Una amplia variedad de puertos abiertos, incluyendo algunos comunes y otros más oscuros como fjicl-tep-a (puerto 1901/tcp) y proremote (puerto 8183/tcp).
    Sistema operativo: LG Electronics