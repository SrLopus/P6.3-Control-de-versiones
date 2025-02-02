# API REST - Administración de Usuarios - Práctica 6.3  

Esta API REST permite gestionar usuarios a través de las operaciones básicas **CRUD** (Crear, Leer, Actualizar y Eliminar).  

## 📌 Descripción del Proyecto  

El proyecto consiste en una API sencilla diseñada para la administración de usuarios. Se estructura en dos componentes principales:  

## 🌐 Frontend  
- Utiliza un servidor **Nginx**, ideal para servir contenido estático de manera eficiente.  
- Se encarga de gestionar el código **HTML, CSS y JavaScript**, además de realizar las validaciones necesarias en el cliente.  

## 🖥️ Backend  
- Basado en **Node.js**, este componente maneja toda la lógica de negocio.  
- Procesa los datos enviados desde el frontend a través de formularios y los almacena en una base de datos simulada representada por un archivo **JSON**.  

## 🐳 Archivo `docker-compose.yml`  
- **Backend**: Se configura para construir la aplicación a partir de la carpeta **backend**, donde se encuentra un **Dockerfile** que descarga y configura la imagen de **Node.js** desde **DockerHub**.  
- **Frontend**: Se define para utilizar una imagen de **Nginx** obtenida de **DockerHub**, que se encargará de servir la interfaz gráfica de la aplicación.