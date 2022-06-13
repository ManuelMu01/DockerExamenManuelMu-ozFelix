# Docker Examen Manuel Muñoz Felix

# APARTADO 1
## Ejercicio 1
#### Descargar  una imagen de manera previa
#### Descargaremos la imagen con un docker pull nombre
h1

#### Crear un contenedor de ubuntu:18.04 y tener acceso a un shell en él.
#### Para hacer esto haremos docker run -it ubuntu:18.04 /bin/bash el -it es para tener acceso a el
h2

## Ejercicio 2
#### Crear un contenedor de centOs:18.04 y listar el contendido
### Para hacerlo tendremos que hacer un docker run como antes pero añadiendo ls para listarlo
h3

## Ejercicio 3
#### Crear un contenedor de httpd (Servidor Apache)
### Para hacerlo tendremos que hacer un docker run httpd
h4

## Ejercicio 4
#### Crear un contenedor de  debian 9 y mostrar el contenido de una carpeta 
### Para hacerlo tendremos que hacer un docker run -it -w /etc debian:9 ls
h5
### Mostrar los contenedores en ejecución 
docker ps
### Mostrar todos los contenedores creados ya estén en ejecución
docker ps -a
h6
(vienen las dos en una foto)

### APARTADO 2
### DOCKERFILE Proyecto Tomcat
#### Creamos una carpeta entramos y cremaos un dockerfild con vi Dockerfile
h7
#### Rellenamos todo 
h8
Hacemos un build
h9
Hacemos un docker images para mirar que la tengamos
h10
Subir la imagen
Hacemos un docker login
h11
generar una imagen y subir la imagen 
copy  se puede eliminar
