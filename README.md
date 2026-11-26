# Mi App WordPress con Nginx + PHP-FPM + MySQL en Docker

## Descripción

Aplicación WordPress desplegada en contenedores utilizando Docker Compose.

## Servicios

- Nginx (servidor web, puerto 8080)
- PHP-FPM (ejecutor de scripts PHP)
- MariaDB (base de datos)

## Instrucciones de despliegue

1. Clonar el repositorio:

   git clone https://github.com/paulaamarttin/miapp-docker.git
   cd miapp-docker

2. Levantar los contenedores:

   docker compose up -d

3. Acceder en el navegador:

   http://localhost:8080/
