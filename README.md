# Proyecto de Red Empresarial – Cisco Packet Tracer

Simulación de una red empresarial realizada en Cisco Packet Tracer, que implementa segmentación por VLAN, enrutamiento, redundancia y servicios de red, con el objetivo de representar la infraestructura de una empresa con múltiples departamentos.

## Descripción general

La topología representa una red corporativa con un switch de distribución central conectado a múltiples switches de acceso correspondientes a distintas áreas de la empresa, como Ventas, Administración y Gerencia.

Se implementa conexión hacia un proveedor ISP, redundancia con HSRP, servidor interno y dispositivos finales como PCs, teléfonos IP y puntos de acceso inalámbrico.

## Características implementadas

- Segmentación de red mediante VLANs
- Switch de distribución capa 3
- Enrutamiento entre VLANs
- Redundancia con HSRP
- Conexión a ISP
- Servidor interno (WEB / DNS)
- Telefonía IP
- Access Points para red inalámbrica
- DHCP / direccionamiento IP manual
- Topología jerárquica (Core / Distribution / Access)

## Estructura de la red

- Router ISP conectado a routers de borde
- Routers con HSRP para alta disponibilidad
- Switch de distribución central
- Switches de acceso por departamento
- Servidor conectado a la red principal
- PCs, teléfonos IP y Access Points como clientes

## Herramientas utilizadas

- Cisco Packet Tracer
- Configuración CLI de routers y switches
- VLAN / Routing / HSRP / DHCP

## Autor

Benjamín Pérez  
Estudiante de Ingeniería Civil en Computación e Informática
