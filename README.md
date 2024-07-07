# Servidor de Gestión de Personas

Este proyecto es un servidor backend desarrollado en Node.js utilizando Express, diseñado para gestionar un sistema de información de personas. Permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre una base de datos MySQL.


## Características

- **CRUD Completo:** Permite insertar, modificar, seleccionar y eliminar datos de personas en la base de datos.
- **Validación de Datos:** Asegura que todos los datos necesarios sean proporcionados antes de realizar operaciones en la base de datos.
- **CORS Habilitado:** Configurado para permitir solicitudes de cualquier origen, facilitando la integración con frontends en diferentes dominios.
- **Manejo de Errores:** Incluye middleware para manejar errores y solicitudes a rutas no definidas.

## Requisitos Previos

Para ejecutar este proyecto, necesitarás Node.js y MySQL instalados en tu sistema.
        - npm init -y
        - npm install express mysql2

## Instalación

1. Clona este repositorio.
2. Navega hasta la carpeta del proyecto y ejecuta `npm install` para instalar las dependencias.
3. Asegúrate de tener una base de datos MySQL corriendo y configura las credenciales de conexión en el archivo `server.js`.
4. Ejecuta `node server.js` para iniciar el servidor.

## Uso

Una vez que el servidor esté corriendo, estará disponible en `http://localhost:3000`. Puedes utilizar herramientas como Postman o cURL para hacer solicitudes HTTP a los diferentes endpoints definidos para insertar, modificar, seleccionar y eliminar datos.

## Autor

Marlon Vera 2024.