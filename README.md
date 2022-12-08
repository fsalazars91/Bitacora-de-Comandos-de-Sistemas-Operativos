# Bitacora-de-Comandos-de-Sistemas-Operativos
|  Comando  |  Uso  |
---------------------
|     sudo  | ejecutar programa como administrador|
----------------------
|     ls    | Lista de archivos y carpetas del directorio|
----------------------
|     pwd   | para saber la ruta en donde estoy en ese momento|
----------------------
cd /| change directory (cd ..)
----------------------
nano| editor de texto
----------------------
cat y nombre del archivo |para ver contenido del archivo
----------------------
rm y nombre del archivo | para remover o eliminar un archivo o carpetas(tengo que estar fuera de la carpet) rm Mario -R(para borrar carpetas) cuando me dice q es directorio
----------------------
clear |borrar todo el historial de la terminal
----------------------
top |para ver los procesos corriendo
----------------------
ps -aux |un print de los procesos en el momento
----------------------
pstree | mostrar los procesos como arbol
----------------------
kill -9 y el process number |para matar el proceso
----------------------
ip a | ver la direccion ip
----------------------
sudo apt update && sudo apt upgrade| para poder actualizar apps
----------------------
sudo apt install |para instalar cosas
----------------------
man (apt, ls) | manual de que comandos hay y como usarlos
----------------------
sudo su |root para tener un usuario de administrador
----------------------
whoami |para cambiar de un usuario a otro y no se ocupa el sudo para correr los comandos
----------------------
exit |salir del root del whoami
----------------------
more (nombre archivo)| para desplegar el contenido de un archivo y que sea muy largo
----------------------
| |concatenar comandos
----------------------
tail -n 5 (nombre archivo) |lineas al final del texto del archivo (archivos de texto)
----------------------
head -n x (nombre del archivo) |ver las primeras lineas (archivos de texto)
----------------------
cp (nombre del archivo y el nombre nuevo) |copiar archivos
----------------------
mv (nombre del archivo) donde quiere ponerlo| mover archivos
----------------------
cd (donde quiero ir) | moverme entre carpetas, directorios
----------------------
sudo adduser (nombre de usuario) | crear otro usuario 
----------------------
sudo passwd (nombre usuario) | cambiar password
----------------------
history |historial de todos los comandos
----------------------
history | grep (comandos)|permite buscar el historial de los comandos en especifico
----------------------
telnet towel.blinkenlights.nl | Starwars
----------------------
/var/log/dmesg |  en este archivo se almacena la información que genera el kernel durante el arranque del sistema. Podemos ver su contenido con el comando dmesg:
----------------------
La opción -r elimina de forma recursiva las carpetas y su contenido.
----------------------
ps aux| procesos
----------------------
sudo du -h (directorio) ./* >>(archivo de txt)| para que el resultado se guarde en un txt
----------------------
find . -name "libQt5SocketIo.so.5"| buscar de manera recursiva
----------------------
df-h | ver espacio en disco
----------------------
useradd| agregar usuario
----------------------
parametros 

ls -l: imprimir en lista
----------------------
ls -a: muestra muchos archivos
----------------------
Docker commands

----------------------
docker create crea un contenedor pero no lo comienza.
----------------------
docker rename permite renombrar al contenedor.
----------------------
docker run crea y comienza un contenedor en una operación.
----------------------
docker rm borra un contenedor.
----------------------
docker update actualiza los recursos limitados de un contenedor.
----------------------
Comenzando y deteniendo
----------------------
docker start| comienza un contenedor si se cayó o salió.
----------------------
docker stop |detiene un contenedor.
----------------------
docker restart |detiene y comienza un contenedor.
----------------------
docker pause| pausa un contenedor corriendo, "lo congela". 
----------------------
docker unpause |quita la pausa de un contenedor corriendo.
----------------------
docker wait |bloquea hasta que un contenedor corriendo se detiene.
----------------------
docker kill |envía una SIGKILL a un contenedor corriendo.
----------------------
docker attach |se conecta a un contenedor corriendo.
----------------------

Info
----------------------
docker ps |muestra los contenedores corriendo.
----------------------
docker logs| obtiene logs de un container.
----------------------
docker inspect| observa la info en un contenedor.
----------------------
docker events | obtiene eventos de un contenedor.
----------------------
docker port | muestra el puerto publico de un contenedor.
----------------------
docker top  | muestra los procesos corriendo en un contenedor.
----------------------
docker stats  | muestra las estadisticas de recursos usados por contenedor.
----------------------
docker diff | muestra los archivos cambiados en el FS del contenedor.
----------------------
docker ps -a  |  muestra todos los contenedores corriendo y detenidos.
----------------------
docker stats --all | muestra una lista de los contenedores corriendo.
----------------------

Images
----------------------
Images son solo templates para contenedores de docker.
----------------------
Lifecycle
----------------------
docker images| muestra todas las imagenes
----------------------
docker import | crea una imagen de un tarball.
----------------------
docker build | crea imagen de un  Dockerfile.
----------------------
docker commit | crea imagen de un contenedor, pausandolo temporalmente si esta corriendo.
----------------------
docker rmi | remueve una imagen.
----------------------
docker load | carga una imagen de un archivo tar como STDIN, incluyendo imagenes y tags.
----------------------
docker save | salva una imagen a un archivo tar a STDOUT con todas las capas padre, tags y versiones.
----------------------
Info
----------------------
docker history|  muestra el historial de una imagen.
----------------------
docker tag | taggea una imagen a un nombre asignado.
----------------------

Referencias: 
https://cerebro-digital.com/panel/knowledgebase/63/Comandos-frecuentes-de-Docker.html
