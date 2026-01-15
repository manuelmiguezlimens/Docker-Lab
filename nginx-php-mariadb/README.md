# 🐳 Docker Stack: Nginx + PHP + MariaDB

## 📌 Descripción
Este laboratorio muestra el despliegue de un **stack completo de servicios**
utilizando **Docker Compose**, compuesto por un servidor web **Nginx**, una
aplicación **PHP (PHP-FPM)** y una base de datos **MariaDB**.

El objetivo es simular una arquitectura real utilizada en entornos de producción
y demostrar el uso de contenedores, redes y volúmenes en Docker.

---

## 🎯 Objetivos del laboratorio
- 🚀 Desplegar múltiples servicios con Docker Compose
- 🌐 Configurar Nginx como servidor web
- 🧠 Ejecutar una aplicación PHP con PHP-FPM
- 🗄️ Usar MariaDB con persistencia de datos
- 🔗 Implementar redes y volúmenes Docker

---

## 🧪 Estructura del proyecto

```text
nginx-php-mariadb/
├── docker-compose.yml
├── nginx/
│   └── default.conf
├── app/
│   └── index.php
└── README.md
```

---

## 🛠️ Requisitos
- Docker
- Docker compose (v2)
- Sitema operativo 

---

## ▶️ Despliegue del stack

1. Acceder al directorio del proyecto
2. Levantar los servicios
3. Acceder desde el navegador a http://localhost:8080

---

## 🔧 Componentes del stack
- 🌐 Nginx

    - Servidor web

    - Escucha en el puerto 8080 del host

    - Enruta peticiones PHP hacia PHP-FPM

- 🧠 PHP-FPM

    - Ejecuta la aplicación PHP

    - Comparte volumen con Nginx

- 🗄️ MariaDB

    - Base de datos relacional

    - Datos persistentes mediante volumen Docker

--- 
## 🏢 Caso de uso real

Este stack es un ejemplo típico de:

- Aplicaciones web LAMP/LEMP modernizadas con Docker

- Entornos de desarrollo local

- Pruebas y validaciones previas a producción

--- 

## 🚀 Posibles mejoras

- 📄 Uso de variables de entorno con .env

- 🩺 Healthchecks

- 📝 Gestión de logs

- 🔐 Hardening del stack

- 🌍 Despliegue en servidor remoto

---

👤 Autor

Manuel Míguez Liméns

[GitHub](https://github.com/manuelmiguezlimens) || [LinkedIn](https://www.linkedin.com/in/manuelmiguezlimens/) || [Gmail](mailto:miguezlimensmanuel@gmail.com)