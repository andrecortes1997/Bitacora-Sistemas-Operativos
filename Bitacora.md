# Sistemas Operativos Bitacora de Comandos
--------------------------------------------
![Ubuntu](https://github.com/andrecortes1997/Bitacora-Sistemas-Operativos/blob/master/Ubuntu-Vertical-white-br-orange.sh_.png?raw=true) 
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
| `adduser ` | agregar usuarios. |`$ adduser andre`|

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

![Archivos y Directorios](https://www.faqforge.com/wp-content/uploads/2017/03/power-off-dialog-ubuntu-button-press.png)

## Apagar (Reiniciar Sistema o Cerrar Sesión)

| Comandos 				| Descripcion |  Ejemplos   |
| ------   			 	| ----------- | ----------- |
| `shutdown ` | Apagar el sistema. |`$ shutdown -h now`|
| `reboot` | Reiniciar el sistema. |`$ reboot `|
| `logout` | Cerrar sesión. |`$ logout`|
| `shutdown -h hours:minutes &` | Apagado planificado del sistema. |`$ shutdown -h hours:minutes & `|
| `halt` | Apagar el sistema. |`$ halt`|
| `shutdown -c` | Cancelar un apagado planificado del sistema. |`$ shutdown -c`|

![Archivos y Directorios](https://icons.iconarchive.com/icons/umut-pulat/tulliana-2/128/cd-writer-mount-icon.png)
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
| `du -sk` | Mostrar el tamaño de los ficheros y directorios ordenados
por tamaño.. |`$ du -sk * "pipe" sort -rn `|


```bash
ls /Documents
```
