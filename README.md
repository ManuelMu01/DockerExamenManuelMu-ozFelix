# Docker Examen Manuel Muñoz Felix

# APARTADO 1
## Ejercicio 1
#### Descargar  una imagen de manera previa
#### Descargaremos la imagen con un docker pull nombre

![h1](https://user-images.githubusercontent.com/91874537/173314552-02b42de9-ccd8-4c71-89c7-2f3cafc6de08.PNG)

#### Crear un contenedor de ubuntu:18.04 y tener acceso a un shell en él.
#### Para hacer esto haremos docker run -it ubuntu:18.04 /bin/bash el -it es para tener acceso a el

![h2](https://user-images.githubusercontent.com/91874537/173314575-b58429a2-ddea-436c-9e29-91e1582bc38f.PNG)

## Ejercicio 2
#### Crear un contenedor de centOs:18.04 y listar el contendido
### Para hacerlo tendremos que hacer un docker run como antes pero añadiendo ls para listarlo

![h3](https://user-images.githubusercontent.com/91874537/173314622-e0c358f1-5cc3-4cfb-844a-42e65e0d6861.PNG)

## Ejercicio 3
#### Crear un contenedor de httpd (Servidor Apache)
### Para hacerlo tendremos que hacer un docker run httpd

![h4](https://user-images.githubusercontent.com/91874537/173314657-72659485-be69-43af-b495-e388fe2b408f.PNG)

## Ejercicio 4
#### Crear un contenedor de  debian 9 y mostrar el contenido de una carpeta 
### Para hacerlo tendremos que hacer un docker run -it -w /etc debian:9 ls

![h5](https://user-images.githubusercontent.com/91874537/173314685-7b08d4ae-71af-4b5c-96b9-5cc3174923a9.PNG)

### Mostrar los contenedores en ejecución 
docker ps
### Mostrar todos los contenedores creados ya estén en ejecución
docker ps -a

![h6](https://user-images.githubusercontent.com/91874537/173314742-e4c39a43-f6e4-4746-858b-91d720f1d775.PNG)

(vienen las dos en una foto)

### APARTADO 2
### DOCKERFILE Proyecto Tomcat
#### Creamos una carpeta entramos y cremaos un dockerfild con vi Dockerfile

![h7](https://user-images.githubusercontent.com/91874537/173314779-803e5162-c864-49f4-bb4b-7e5c500d4bcd.PNG)

#### Rellenamos todo 

![h8](https://user-images.githubusercontent.com/91874537/173314797-82f3bdec-5655-4ace-9b0d-bfbf2ad7b574.PNG)

#### Hacemos un build

![h9](https://user-images.githubusercontent.com/91874537/173314816-d4c09274-591f-41ac-9e6b-f4e5a29c9ff1.PNG)

#### Hacemos un docker images para mirar que la tengamos

![h10](https://user-images.githubusercontent.com/91874537/173314833-44336648-2d32-4dd6-bb72-2e64f2cc73c6.PNG)

### Subir la imagen
#### Hacemos un docker login

![h11](https://user-images.githubusercontent.com/91874537/173314861-0f3b6c9f-6e7f-48c5-a4a6-c62f9153ef1b.PNG)

#### Hacemos un tag para preparar la imagen para que sea aceptada en este registro público

![h12](https://user-images.githubusercontent.com/91874537/173314894-25b4801e-6284-4379-a9aa-f3c86f986ac0.PNG)

#### Ya estaria lista para subirse 
#### Hacemos un push manu1661/2703bbe9e9d4:v1 para subirlo

![h13](https://user-images.githubusercontent.com/91874537/173314927-f36513cd-a367-4990-83a9-e1c09cc7798c.PNG)

Ya lo tendiramos en el Docker Hub
[https://hub.docker.com/u/manu1661](https://hub.docker.com/r/manu1661/2703bbe9e9d4)

![h14](https://user-images.githubusercontent.com/91874537/173314974-40bb9014-23b6-42c7-a0a0-8d5d1b0a168e.PNG)
