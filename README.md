# Máquina virtual con Windows 7 y Nacional Software para Test

Máquina virtual con Windows 7 y Nacional Software para Testear las funcionalidades del programa antes de instalarlo definitivamente en una computadora/servidor


## Instalación

Para poder ejecutar la maquina virtual se debe:

1. Instalar VirtualBox

2. Descargar la MV desde:  https://uadeeduar-my.sharepoint.com/:u:/g/personal/abustos_uade_edu_ar/EWCTAX4dwzFPnWxC3QO2DIoBuzNmekUM8-9a1gf_JXjP1g?e=BHimMs

3. Abrir la MV desde VirtualBox 


## Configuraciones

Se realizaron solamente configuraciones básicas como definir una IP privada Fija `192.160.0.100`


### Conexiones desde otra PC (local)

Para conectarse desde otra PC dentro de la Red local se debe redirigir a la PC/servidor que tiene las bases de datos de los clientes.

Se debe configurar de la siguiente manera:

- En la conexión en `Servidor` va la IP Fija local `192.160.0.100`

- En Puerto `3306`

- Se debe hacer click en `Conectar`


### Conexiones desde otra PC (Exterior)

- Se debe realizar una redirección del Puerto `3306` a la PC/Servidor a `192.160.0.100`

- Se debe tener una IP Pública Fija o un DDNS
  
  - En la conexión en `Servidor` va la IP fija o DDNS
  
  - En Puerto `3306`
  
  - Se debe hacer click en `Conectar`


#### Conexiones desde el Exterior con algún cliente SQL (como workbench, DBeaver, Python, etc)

- Se debe realizar la conexión hacia la IP Fija local para utilizarlo bajo red local o con la DDNS para conectarse desde cualquier red.

- El usuario y contraseña es `root`
  
  La ventaja de hacerlo de esta manera es que se pueden realizar Importaciones/Exportaciones de información masiva más avanzadas

---


## Aclaraciones

- La utilización de la maquina virtual corre bajo la responsabilidad del que lo ejecuta.

- La finalidad de este proyecto es con fines educativos y de testing del Sistema contable. NO ES APTO PARA LA EJECUCIÓN EN PRODUCCIÓN
  
---
  
  
## Links de Interés:

- Link de invitación al grupo de RPA en Discord: https://discord.gg/KVYyryvAcD

- Link de invitación al grupo de RPA en WhatsApp: https://chat.whatsapp.com/IekktfvfTNLCkdIagO6xz3

- Tutorial de Descarga de Bots desde Uipath: https://youtu.be/hD5BH7YzABw

- Tutorial de Instalación y descarga de Repositorios con Git: https://youtu.be/ujk27tRdA80

---

Cualquier cosa pueden contactarme en:

- https://www.linkedin.com/in/agust%C3%ADn-bustos-piasentini-468446122/

- https://www.youtube.com/user/agustinbustosp

- whatsapp al https://wa.me/+5493764224695

---

<br/>

## 💰 Acepto donaciones para mantener el proyecto libre y gratuito

<br/>

[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/agustinbustosp) <!-- [<img src="http://ketekipo.com.ar/wp-content/uploads/2020/05/mercado-pago.png" alt="Image" height="30" width="100\">](https://paypal.me/paypal.me/agustinbustosp) -->

[![Invitame un café en cafecito.app](https://cdn.cafecito.app/imgs/buttons/button_5.svg)](https://cafecito.app/abustos)

<br/>

## 💰 Y También en Pesos Argentinos

<br/>

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%20100-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/2JBdGez)

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%20500-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/2CwfjKE)

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%201.000-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/21Xvpig)

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%205.000-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/1s4D4mM)

[![Mercado Pago](https://img.shields.io/badge/Mercado%20Pago%2010.000-009ee3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://mpago.la/1n9cimr)


