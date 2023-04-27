### DDoS-PHP-Script ###

<div>
  <img src="https://insidetrade.co/wp-content/media/2020/02/DOS-Attack.png" width="600" height="300"/>
</div>

### Acerca del proyecto: ###
Este proyecto fue desarrollado para simular un ataque DDoS UDP flood, utilizando como lenguaje base PHP. La idea es que este código sea utilizado únicamente con fines educativos. Los desarrolladores no se hacen responsables del mal uso que se le de a este script.

### Licenciamiento ###
Liberado y distribuido bajo licencia GNU v2.

## Modo de uso ###
Desde el servidor web de pruebas visitar la siguiente url:
`http://127.0.0.1/ddos.php?pass=apple&host=TARGET&port=PORT&time=SECONDS&packet=NUMBER&bytes=NUMBER`

Desde la terminal (Windows / Linux / Mac):
`php ./ddos.php host=TARGET port=PORT time=SECONDS packet=NUMBER bytes=NUMBER`

### Parámetros ###
<pre>help	Print this help summary page
host	REQUIRED specify IP or HOSTNAME
pass	REQUIRED only if used from webserver
port	OPTIONAL if not specified a random ports will be selected
time	OPTIONAL seconds to keep the DDoS alive, required if packet is not used
packet	OPTIONAL number of packets to send to the target, required if time is not used
bytes	OPTIONAL size of the packet to send, defualt: 65000
format	OPTIONAL output format, (text,json,xml), default: text
output	OPTIONAL logfile, save the output to file
verbose	OPTIONAL 0: debug, 1:info, 2:notice, 3:warning, 4:error, default: info

Nota: 	Si se especifican tanto la hora como el paquete, sólo se utilizará la hora.
</pre>

### Requiremientos ###
- PHP 5.4 o superior

### Lista de tareas ###
- Introducir una función de registro en el archivo

### Créditos ###
* [Andrea Draghetti](https://twitter.com/AndreaDraghetti) is the creator of the project
* [@TheZer0](https://github.com/TheZ3ro) to support for coding;
* [@Smaury](https://github.com/smaury) to support for coding;
* [@moty66](https://github.com/moty66) to support for coding;
* [@AxissXs](https://github.com/AxissXs) to support for coding.

### Aviso legal ###
Esta herramienta está escrita con fines educativos únicamente, **por favor** utilícela de buena fe.

### Invítame un café: ###
<div id="badges">
  <a href="https://www.buymeacoffee.com/elblogden4p5t3r" target="_blank">
    <img src="https://img.shields.io/badge/buymeacoffee-yellow?style=for-the-badge&logo=buymeacoffee&logoColor=white" alt="LinkedIn Badge"/>
  </a>
</div>
