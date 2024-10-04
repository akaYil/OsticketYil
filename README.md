# OsticketYil
Tarea 1.2 - Extension de API OSTICKET

# API de Gestión de Usuarios para OSTicket

Este proyecto proporciona una extensión del API para OSTicket que permite la creación de nuevos usuarios a través de solicitudes JSON. El objetivo es facilitar la gestión de usuarios dentro de un sistema de tickets.

## Índice

- [Características](#características)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Ejemplo de JSON](#ejemplo-de-json)
- [Contribución](#contribución)
- [Licencia](#licencia)

## Características

- Crear nuevos usuarios con correo electrónico, nombre completo, número de teléfono, zona horaria y contraseña.
- Validación de contraseña mediante confirmación.
- Implementación sencilla mediante solicitudes POST al endpoint del API.

## Tecnologías Utilizadas

- PHP
- OSTicket
- XAMPP
- MySQL

## Requisitos

- XAMPP instalado en tu máquina.
- OSTicket configurado y funcionando.
- Acceso a la API de OSTicket.

## Instalación

1. Clona este repositorio en tu máquina local:
    ```bash
    git clone https://github.com/tu_usuario/tu_repositorio.git
    ```
   
2. Coloca los archivos en la carpeta `htdocs` de tu instalación de XAMPP.

3. Asegúrate de que OSTicket esté correctamente configurado.

## Uso

Para crear un nuevo usuario, envía una solicitud POST al siguiente endpoint:

http://localhost/osticket/api/users.json


Asegúrate de incluir el siguiente encabezado en tu solicitud:


Asegúrate de incluir el siguiente encabezado en tu solicitud:


### Ejemplo de JSON

Aquí tienes un ejemplo de cómo debe ser el cuerpo de la solicitud JSON:

```json
{
    "email": "nuevo_usuario2024@ejemplo.com",
    "full_name": "Usuario Ejemplo 2024",
    "phone": "9876543210",
    "timezone": "America/Chicago",
    "password": "MiContraseñaSegura123",
    "confirm_password": "MiContraseñaSegura123"
}


### **Instrucciones para Personalizar**
- Cambia `tu_usuario` y `tu_repositorio` en el enlace de clonación al nombre de tu usuario y el repositorio que hayas creado en GitHub.
- Ajusta el contenido según las características específicas de tu proyecto y la estructura que hayas utilizado.
- Si tienes más detalles sobre tecnologías o requisitos, añádelos para mayor claridad.

Este formato de README te ayudará a documentar tu proyecto de manera clara y profesional. Si necesitas realizar más ajustes, ¡dímelo!


