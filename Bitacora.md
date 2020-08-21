# Sistemas Operativos Bitacora de Comandos
--------------------------------------------
![Ubuntu](https://images.vexels.com/media/users/3/140692/isolated/preview/72d1f12edf758d24f5b6db73bac4f297-logo-de-linux-by-vexels.png) 
# Lista de Comandos

![Monitoreo y Sistema](https://www.uthdynasty.com/wp-content/uploads/2014/12/Data-Mining.png)

## Monitoreo y Sistema
| Comandos 				| Descripcion |  Ejemplos   |
| ------   			 	| ----------- | ----------- |
| `sudo apt install`   	| La utilidad `apt install` es un programa de línea de comandos de administración de paquetes potente y gratuito, que se utiliza para trabajar con la biblioteca APT (Advanced Packaging Tool) de Ubuntu para realizar la instalación de nuevos paquetes de software. | `$ sudo apt install wireshark` |
| `sudo apt update`  	| El comando se utiliza para descargar información del paquete de todas las fuentes configuradas. | `$ sudo apt update` |
| `sudop apt upgrade`   | Se utiliza para instalar actualizaciones disponibles de todos los paquetes actualmente instalados en el sistema desde las fuentes configuradas a través del archivo sources.list.file. |`$ sudop apt upgrade`|
| `lsb_release -a` | Sirve para saber la version de ubuntu . |`$ lsb_release -a`|
| `kill -9` | matar procesos para cerrar programas. |`$ kill -9 "PID del proceso"`|
| `man` | nos describe como funcionan otros comandos. |`$ man mkdir`|
| `whoami ` | nos describe como funcionan otros comandos. |`$ man mkdir`|
| `top` | mostrar las tareas de linux usando la mayoría cpu. |`$ top`|
| `ps -aux` | Mostrar Procesos corriendo . |`$ ps -aux`|
| `ps -aux grep` | ps -aux con grep ayuda a buscar algo especifico en la lista de procesos . |`$ ps -aux grep firefox `|

![Archivos y Directorios](https://icons.iconarchive.com/icons/franksouza183/fs/256/Places-folder-ubuntu-icon.png)

## Archivos y Directorios

| Comandos 				| Descripcion |  Ejemplos   |
| ------   			 	| ----------- | ----------- |
| `ls` | Listar carpetas en cualquier ruta. |`$ ls -l /usr/bin `|
| `ls -l` | Muestra las carpetas en forma de lista con mas detalles (Tamaño, fecha). |`$ ls -l`|
| `ls -a` | Muestra las carpteas  y los archivos ocultos. |`$ ls -a`|
| `mkdir` | Crear carpetas. |`$ mkdir "nombre de la carpeta"`|
| `pwd` | Muestra la ruta del directorio actual. |`$ pwd`|
| `touch ` | Comando para crear archivos [Nombre del archivo y extension] . |`$ touch helloworld.py`|
| `mkdir` | Crear carpetas. |`$ mkdir "nombre de la carpeta"`|
| `top` | Muestra los primeros comandos. |`$ top`|
| `cd /home` | Entrar en el directorio. |`$ .cd /home`|
| `cd ..` | Retroceder un nivel. |`$ cd ..`|
| `rm` | Borrar el fichero llamado ‘file1′. |`$ rm -f file1`|
| `tail ` | Ver las 10 últimas líneas de un fichero. |`$ tail -n 10 /var/log/syslog`|
| `head` | Ver las 10 primeras líneas de un fichero. |`$ head -10 file1`|
| `alias` | Son como atajos personalizados que se utilizan para representar un comando (o un conjunto de comandos) ejecutados con o sin opciones personalizadas. |`$ alias wr=”cd /var/www/html”`|
| `history ` | Listado de todos los comandos digitados. |`$ history`|
| `!! ` | Correr ultimo comando utilizado. |`$ !!`|
| `cat` | Mostrar contenido de archivos. |`$ cat /proc/cpuinfo`|
| `mv` | Renombrar o mover un fichero o carpeta (directorio) |`$ .mv dir1 new_dir`|
| `find` |  Buscar fichero y directorio a partir de la raíz del sistema. |`$ find / -name file1`|
| `find` | Buscar ficheros y directorios pertenecientes al usuario ‘user1′. |`$ find / -user user1`|
| `locate` | Encuentra ficheros con extensión ‘.ps’ ejecutados primeramente con el command ‘updatedb’. |`$ locate \ *.ps`|
| `ls -lh` | Mostrar permisos. |`$ ls -lh`|
| `chmod ` |  Colocar permisos de lectura ®, escritura (w) y ejecución(x) al propietario (u), al grupo (g) y a otros (o) sobre el directorio ‘directory1′. |`$ chmod ugo+rwx directory1`|
| `chmod ` |  Quitar permiso de lectura ®, escritura (w) y (x) ejecución al grupo (g) y otros (o) sobre el directorio ‘directory1′. |`$ chmod go-rwx directory1`|
| `chown` |  Cambiar el dueño de un fichero. |`$ chown user1 file1`|
| `chown` | Cambiar el propietario de un directorio y de todos los ficheros y directorios contenidos dentro. |`$ chown -R user1 directory1`|
| `dpkg` | Instalar / actualizar un paquete deb. |`$ dpkg -i package.deb`|
| `dpkg` | Eliminar un paquete deb del sistema |`$ dpkg -r package_name`|


![Apagar (Reiniciar Sistema o Cerrar Sesión)](https://www.faqforge.com/wp-content/uploads/2017/03/power-off-dialog-ubuntu-button-press.png)

## Apagar (Reiniciar Sistema o Cerrar Sesión)

| Comandos 				| Descripcion |  Ejemplos   |
| ------   			 	| ----------- | ----------- |
| `shutdown ` | Apagar el sistema. |`$ shutdown -h now`|
| `reboot` | Reiniciar el sistema. |`$ reboot `|
| `logout` | Cerrar sesión. |`$ logout`|
| `shutdown -h hours:minutes &` | Apagado planificado del sistema. |`$ shutdown -h hours:minutes & `|
| `halt` | Apagar el sistema. |`$ halt`|
| `shutdown -c` | Cancelar un apagado planificado del sistema. |`$ shutdown -c`|

![Montando un sistema de ficheros](https://icons.iconarchive.com/icons/umut-pulat/tulliana-2/128/cd-writer-mount-icon.png)
## Montando un sistema de ficheros

| Comandos 				| Descripcion |  Ejemplos   |
| ------   			 	| ----------- | ----------- |
| `mount` | Montar un disco llamado hda2. |`$ mount /dev/hda2 /mnt/hda2 `|
| `umount` |  Desmontar un disco llamado hda2. |`$ umount /dev/hda2`|
| `mount /dev/sda1 /mnt/usbdisk ` | Montar un usb pen-drive o una memoria. |`$ mount /dev/sda1 /mnt/usbdisk `|


![Espacio de Disco](https://icon-library.com/images/linux-server-icon/linux-server-icon-2.jpg)
## Espacio de Disco

| Comandos 				| Descripcion |  Ejemplos   |
| ------   			 	| ----------- | ----------- |
| `df -h` | Mostrar una lista de las particiones montadas. |`$ df -h`|
| `du -sh dir1:` | Estimar el espacio usado por el directorio ‘dir1′. |`$ du -sh dir1: `|
| `du -sk` | Mostrar el tamaño de los ficheros y directorios ordenados por tamaño. |`$ du -sk * "pipe" sort -rn `|

![Usuarios y Grupos](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQJ6-IWIzvvi3l0tWgoqbtbQN6gukza_fYICg&usqp=CAU)
## Usuarios y Grupos

| Comandos 				| Descripcion |  Ejemplos   |
| ------   			 	| ----------- | ----------- |
| `groupadd` | Crea un nuevo grupo. |`$ groupadd nombre_del_grupo `|
| `groupdel` | Borrar un grupo. |`$ groupdel nombre_del_grupo`|
| `adduser ` | Agregar usuarios. |`$ adduser andre`|
| `userdel ` |  Borrar un usuario (‘-r’ elimina el directorio Home).. |`$ userdel -r user1`|
| `passwd` | Cambiar contraseña. |`$ passwd`|
| `passwd user1` | Cambiar la contraseña de un usuario (solamente por root).. |`$ passwd user1`|
| `pwck` | Chequear la sintaxis correcta el formato de fichero de ‘/etc/passwd’ y la existencia de usuarios.. |`$ pwck`|
| `grpck` |  Chequear la sintaxis correcta y el formato del fichero ‘/etc/group’ y la existencia de grupos. |`$ grpck`|
| `newgrp` |  Registra a un nuevo grupo para cambiar el grupo predeterminado de los ficheros creados recientemente. |`$ newgrp nombre_grupo`|


![Archivos y Ficheros comprimidos](https://icons.iconarchive.com/icons/treetog/junior/256/document-compress-icon.png)
## Archivos y Ficheros comprimidos

| Comandos 				| Descripcion |  Ejemplos   |
| ------   			 	| ----------- | ----------- |
| `bunzip2` | Descomprime in fichero llamado ‘file1.bz2′ |`$ bunzip2 file1.bz2`|
| `bzip2` | Comprime un fichero llamado ‘file1′.|`$ bzip2 file1`|
| `gunzip` | Descomprime un fichero llamado ‘file1.gz’. |`$ gunzip file1.gz`|
| `gzip` | Comprime un fichero llamado ‘file1′ |`$ gzip file1:`|
| `unzip` |  |`$ unzip file1.zip`|
| `zip` | Descomprimir un archivo zip.|`$ .zip file1.zip`|
| `rar a file1.rar` | Crear un fichero rar llamado ‘file1.rar’. |`$ rar a file1.rar`|
| `.rar x file1.rar` | Descomprimir archivo rar |`$ .rar x file1.rar`|

![RED](https://icons.iconarchive.com/icons/guillendesign/variations-2/256/Network-On-icon.png)
## RED
| Comandos 				| Descripcion |  Ejemplos   |
| ------   			 	| ----------- | ----------- |
| `ifconfig ` | Mostrar la configuración de una tarjeta de red Ethernet |`$ ifconfig eth0`|
| `ifup` |Activar una interface . |`$ ifup eth0`|
| `ifdown` | Deshabilitar una interface |`$ ifdown eth0`|
| `hostname` | Mostrar el nombre del host del sistema.|`$ hostname`|
| `host` |  Buscar el nombre del host para resolver el nombre a una dirección ip |`$ host www.ejemplo.com`|
| `ip addr` | Mostrar interfaces conectadas con su respectiva IP |`$ ip addr`|
| `nslookup` |  Buscar el nombre del host para resolver el nombre a una direccióm ip y viceversa |`$ nslookup www.ejemplo.com`|
| `ip link show` | Mostar el estado de enlace de todas las interfaces. |`$ ip link show`|
| `netstat ` | Mostrar todas las conexiones de red activas y sus PID. |`$ netstat -tup` |

::: warning
*here be dragons*
:::