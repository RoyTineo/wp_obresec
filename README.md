# 🚀 WordPress con Docker

Este repositorio contiene un entorno base para levantar WordPress en Docker.

## ▶️ Pasos de instalación

1. Clonar el repositorio:
   ```bash
   https://github.com/RoyTineo/wp_obresec.git
   cd wp_obresec
   ```
2. crear el archivo .env real
   cp .env.example .env
   
4. Editar .env y colocar las credenciales reales:
```bash
PROJECT_NAME=wordpress-demo

# Base de datos

MYSQL_DATABASE=wordpress
MYSQL_USER=wpuser
MYSQL_PASSWORD=tu_password_segura
MYSQL_ROOT_PASSWORD=otra_password_segura

# Puerto donde se expondrá WordPress
APP_PORT=8080
```
