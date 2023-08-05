Ejemplo Bitacora de comandos Fabian Lara
| Para que sirve                                | Comandos                            | Ejemplos                                       |
|---------------------------------------|------------------------------------|-------------------------------------------------|
| Ver imágenes instaladas               | `docker images`                   | n/a                                             |
| Ver que lo que se ha digitado            | `history`                         |                                                 |
| Ver carpetas que hay en la ruta       | `ls -l`                           | n/a                                             |
| Actualizar                            | `sudo apt update`                 | `sudo apt update` (actualizar repositorios)    |
| Ver el estado de los contenedores     | `sudo docker ps -a`               | n/a                                             |
| Crear archivo                         | `nano (nombre+extension)`         | `nano Sistemas_Operativos.txt` (crear archivo)  |
| Eliminar contenedores                 | `docker rm ID`                    | n/a                                             |
| Conocer Ip Address                    | `ip a`                            | n/a                                             |
| Abrir monitor de Procesos SO          | `top`                             | n/a                                             |
| Ver Tabla de Reglas del Firewall       | `sudo systemctl cat openvpn-iptables.service` | n/a                                     |
| Iniciar sesión en otro usuario        | `su (usuario)`                    | `su flarar374` (ingrese al usuario flarar374) |
| Detener un contenedor que esté corriendo | `sudo docker stop ID`          | `sudo docker stop d9835647234`                |
| Eliminar contenedor después de cerrado | `docker run --rm image_name`      | n/a                                             |
| Actualizar                            | `sudo apt upgrade`                | `sudo apt upgrade` (instalar actualizaciones)  |
| Ver el estado de los contenedores     | `sudo docker ps -a`               | n/a                                             |
| Dar permisos a los usuarios sobre una carpeta | `sudo chmod 777 -R * /Home/flarar374/` | n/a |
| Explorar contenido de un archivo           | `cat (nombre+extension)`          | `cat Sistemas_Operativos.txt` (ver contenido)   |
| Descargar Archivos                        | `scp usuario@host:/ruta_archivo destino` | `scp mortasoft@192.168.1.158:/home/mortasoft/prueba.txt prueba.txt` (bajar archivos) |
| Limpiar contenidos en Pantalla        | `clear`                           | n/a                                             |
| Buscar en el repositorio de Docker Hub una imagen con ese nombre | `docker search ubuntu` | n/a |
| Mover archivos                                 | `mv (Nombre+ Extension/Directorio)`| `mv Sistemas_Operativos.txt /Home/flarar374/` (mover archivo) |
| Eliminar imágenes de Docker           | `docker rmi Image Image`          | n/a                                             |
| Ver carpetas que hay en la ruta y ocultas | `ls -la`                         | n/a                                             |
| Cambiar la contraseña de usuario         | `sudo passwd (usuario)`           | `sudo passwd flarar374` (cambiar contraseña de flarar374) |
| ubicación del equipo           | `pwd`                             | n/a                                             |
| Instalar tree .                      | `sudo apt install tree`            | `sudo apt install tree` (instala tree)        |
| Ver estatus, iniciar o parar un servicio | `sudo systemctl (status/start/stop)` | `sudo systemctl start openvpn-server@server.service` (iniciar OpenVPN) |
| Crear una carpeta nueva                   | `mkdir (Nombre Carpeta)`           | `mkdir Respositorio_SO` (crear carpeta)        |
| Descargar la imagen del contenedor    | `docker pull ubuntu`              | n/a                                             |
| Copiar archivos                       | `cp (Nombre+ Extension/Directorio)`| `cp Sistemas_Operativos.txt /Home/flarar374/` (copiar archivo) |
| directorio home                  | `cd /home`                        | n/a                                             |
| Iniciar un contenedor que se encuentra detenido | `sudo docker start ID`          | `sudo docker start d9b100f2f636`                |
| Iniciar sesión en otro usuario        | `su (usuario)`                    | `su flarar374` (ingresa al usuario flarar374) |
| Cambiar de directorio                    | `cd (Nombre Carpeta)`       | `cd /Home/flarar374` (ingresa al directorio)   |
| Eliminar todos los contenedores “Exited (0)” | `sudo docker rm $(sudo docker ps -a -f status=exited -q)` | n/a |
| Actualizaciones                           | `sudo apt update`                 | `sudo apt update` (actualiza los repositorios)    |
| Ver la Tabla de Reglas del Firewall       | `sudo systemctl cat openvpn-iptables.service` | n/a                                     |
| Ver el estado de los contenedores     | `sudo docker ps -a`               | n/a                                             |
| Ver las imágenes instaladas               | `docker images`                   | n/a                                             |
| Conocer Ip Address                    | `ip a`                            | n/a                                             |
| Ver carpetas que hay en la ruta y ocultas | `ls -la`                         | n/a                                             |
| Cambiar la contraseña de un usuario         | `sudo passwd (usuario)`           | `sudo passwd Flarar374` (cambiar contraseña de flarar374) |
| Explorar contenido de un archivo           | `cat (nombre+extension)`          | `cat Sistemas_Operativos.txt` (ver contenido)   |
| Mover                                 | `mv (Nombre+ Extension/Directorio)`| `mv Sistemas_Operativos.txt /Home/flarar374/` (mover archivo) |
| Buscar en el repositorio de Docker una imagen con cierto nombre | `docker search ubuntu` | n/a |
| Detener un contenedor que esté corriendo | `sudo docker stop ID`          | `sudo docker stop d9b1937457f6`                |
| Limpiar contenido en Pantalla        | `clear`                           | n/a                                             |
| ubicación del equipo           | `pwd`                             | n/a                                             |
| Eliminar contenedor después de cerrado | `docker run --rm image_name`      | n/a                                             |
| Dar permisos a los usuarios sobre una carpeta | `sudo chmod 777 -R * /Home/flarar374/` | n/a
