# Mean Project

Prueba práctica: Desarrollo  de aplicación API REST para administrar registros de teams y sus miembros

# Git
Este proyecto principal a su vez está compuesto de 2 repositorios, como submodulos de git.

Para agregar los repositorios como submodulos:
git submodule add https://github.com/geralOE/angular-front.git .
git submodule add https://github.com/geralOE/express-server.git .

ó

clonar el repositorio con los submodulos:

git submodule init
git submodule update

# Arquitectura
En la siguiente arquitectura, se utilizan 3 contenedores:
-server-express: contiene una aplicación express, para servir el API Rest
-angular-fron: contiene una aplicación angular, para mostrar el frontend
-mongodb: es un contenedor con mongodb:4.2.3




# Imágenes utilizadas
- node:10
- mongo:4.2.3


Se requiere hacer pull de la siguiente imagen:

docker pull mongo:4.2.3


# Deploy

Para poner en marcha la aplicación es necesario 
docker-compose build
docker-compose up

http://localhost:4200 <-aplicación angular

