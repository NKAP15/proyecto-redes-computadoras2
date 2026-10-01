# proyecto-redes-computadoras2
Diseño y simulación de una red empresarial en Cisco Packet Tracer, implementando enrutamiento, VLAN, DHCP, VoIP, seguridad, firewall y servicios de red.


La red fue organizada en tres zonas principales:

- **INSIDE:** infraestructura interna de la empresa.

- **DMZ:** servidores y servicios de la organización.

- **OUTSIDE:** servicios expuestos hacia el exterior.

La infraestructura integra diferentes edificios, oficinas, servidores, routers, switches y un firewall ASA.

## Tecnologías y conceptos
- Cisco Packet Tracer
- IPv4 y subnetting
- VLAN
- DHCP
- OSPF
- EIGRP
- RIP v2
- BGP
- Redistribución de rutas
- Listas de control de acceso (ACL)
- Firewall ASA
- AAA
- TACACS+
- RADIUS
- Telnet
- Telefonía IP / VoIP
- Dial-peers
- Servidor DNS
- Servidor de correo
- Servidor web
- Manipulación de métricas
 🏗️ Arquitectura de la red

La infraestructura se divide en:

### INSIDE

Incluye cuatro edificios con diferentes oficinas y redes de datos y voz.

Se implementaron VLAN para separar el tráfico de datos y telefonía.

### DMZ

Incluye servicios como:

- Servidor DNS
- Servidor de correo
- Servidor AAA/RADIUS

### OUTSIDE

Incluye el servidor web de la organización y la conexión hacia el exterior.

## 🔐 Seguridad

Se implementaron diferentes mecanismos de seguridad y control de acceso, incluyendo:

- Firewall ASA.

- ACL para restringir comunicación entre oficinas.

- AAA mediante TACACS+ y RADIUS.

- Autenticación local.

- Control de acceso mediante Telnet.

- Restricciones de acceso al servidor web.

## 🌐 Enrutamiento

La infraestructura utiliza diferentes protocolos de enrutamiento y redistribución:
- OSPF
- EIGRP
- RIP v2
- BGP

También se configuraron métricas para controlar determinadas rutas y permitir rutas alternativas.

## 📡 Servicios

El proyecto incluye la configuración y simulación de:
- DHCP
- Telefonía VoIP
- DNS
- Correo electrónico
- Servidor web
- AAA
- Firewall
## 🏗️ Arquitectura de la red

La infraestructura se divide en:
