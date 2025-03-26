# Curso-Docker
Instrucciones DOcker

para instalar imagenes se usa pull
docker pull ubuntu
docker pull debian

se pueden buscar imagenes desde la consola
docker search debian

para ver las imagenes
docker images

para ejecuta el bash de debian
docker run -it debian bash

para ver los contenedores que se estan ejecutando
docker ps

y los que se ha ejecutado 
docker ps -a

para eliminar contenedores...
docker rm 23423423243

para comenzar un contenedor parado
docker start 135125345

parar un contenedor 
docker stop 135125345
