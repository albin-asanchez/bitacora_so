
# Ejemplo de Bitácora de comandos de Sistemas Operativos
Bitácora de comandos para la clase de sistemas operativos

| Comando | Descripción | Ejemplo de uso |
|--|--|--|
| `clear` | Limpia la pantalla de la sesión de consola actual. | `clear` muestra toda la información (gracias al flag `-a`) sobre 
| `cd <ruta de directorio>` | Cambia el directorio actual | `cd ~/Ulacit` para ir a una carpeta llamada Ulacit en el home (~) del usuario actual. |
| `ls <directorio>` | Lista los archivos y directorios que están dentro de un directorio. Si no se pasa ningún directorio cómo parámetro se listan los del directorio actual. | `ls ~/Ulacit` para mostrar todas las carpetas y archivos dentro de la carpeta Ulacit. |
| `cp <origen> <destino>` | Copia un archivo (o directorio si se usa el flag `-r`) de un origen a un destino. | `cp -r ~/Ulacit/* ~/` para copiar todo el contenido de la carpeta llamada Ulacit al home del usuario actual. |
| `echo`| Imprime en pantalla una cadena de texto. | `echo "Hola"` imprimiría Hola en la salida de la terminal. | cambiaría al directorio Documents. |
| `pwd`| Muestra la ruta del directorio actual. | `pwd` podría mostrar algo como `/home/usuario`. |
| `mkdir`| Crea un nuevo directorio. | `mkdir NuevoDirectorio` crearía un directorio llamado "NuevoDirectorio". |
| `rmdir`| Elimina un directorio (debe estar vacío). | `rmdir NuevoDirectorio` eliminaría el directorio "NuevoDirectorio". |
| `rm`| Elimina archivos o directorios.| `rm archivo.txt` eliminaría "archivo.txt".|
| `mv` | Mueve o renombra archivos o directorios. | `mv viejo.txt nuevo.txt` renombraría "viejo.txt" a "nuevo.txt". |
| `cat` | Muestra el contenido de un archivo. | `cat archivo.txt` mostraría el contenido de "archivo.txt". |
| `man` | Muestra el manual del comando especificado. | `man ls` mostraría el manual del comando `ls`. |
| `chmod` | Cambia los permisos de un archivo o directorio. | `chmod 755 archivo.txt` cambiaría los permisos de "archivo.txt".      |
| `chown` | Cambia el propietario y/o grupo de un archivo o directorio. | `chown usuario:grupo archivo.txt` cambiaría el propietario de "archivo.txt". |
| `ps` | Muestra los procesos en ejecución. | `ps aux` mostraría todos los procesos en ejecución. |
| `top` | Muestra información en tiempo real sobre los procesos en ejecución. | `top` mostraría una vista en tiempo real de los procesos. |
| `grep` | Busca patrones específicos en archivos. | `grep "hola" archivo.txt` buscaría la palabra "hola" en "archivo.txt". |
| `df` | Muestra el espacio libre y usado en los sistemas de archivos. | `df -h` mostraría el espacio en un formato legible para humanos. |
| `du` | Estima el uso del espacio de un archivo o directorio. | `du -sh .` mostraría el espacio usado en el directorio actual. |
| `tar` | Crea o extrae archivos comprimidos. | `tar czvf archivo.tar.gz directorio/` comprimiría "directorio". |
| `nano` | Editor de texto en la terminal. | `nano archivo.txt` abriría "archivo.txt" en el editor nano. |
| `sudo` | Ejecuta un comando como superusuario. | `sudo apt update` actualizaría la lista de paquetes en un sistema. |
| `ifconfig` | Muestra o configura información de red. | `ifconfig` mostraría información sobre las interfaces de red. |
| `ping` | Envía paquetes ICMP para probar la conectividad de red. | `ping google.com` enviaría paquetes ICMP a "google.com". |
| `sudo apt-get update` | Actualiza la lista de paquetes disponibles en los repositorios configurados.| `sudo apt-get update`|
| `sudo apt-get upgrade`| Instala las actualizaciones de paquetes que ya están instalados.| `sudo apt-get upgrade` OfficeLibre |
| `sudo apt-get install`| Instala un paquete especificado.| `sudo apt-get install nombre_del_paquete` |
| `sudo useradd -m nombredeusuario -G wheel -p passworddelusuario` | Crea un nuevo usuario en el sistema. | `sudo useradd -m juan -G wheel -p mipassword` crearía un usuario llamado "juan", lo agregaría al grupo "wheel" y establecería "mipassword" como su contraseña. |
| `curl -fsSL`| `curl` es una herramienta que permite hacer solicitudes a URLs desde la línea de comandos. Las opciones `-fsSL` tienen propósitos específicos: `-f` falla en silencio (sin mostrar errores) si la HTTP no es 200 OK, `-s` hace que `curl` opere en modo "silencioso", `-S` muestra errores si ocurren, y `-L` sigue redireccionamientos. | `curl -fsSL https://dominio.com/archivo.txt` descargará el archivo `archivo.txt` desde `https://dominio.com` y lo mostrará en la consola. |
| `sudo gpg --dearmor -o` | `gpg` es una herramienta para cifrar y firmar datos. El flag `--dearmor` se utiliza para convertir archivos ASCII blindados en archivos binarios (y viceversa). Con `-o` se especifica el archivo de salida. `sudo gpg --dearmor -o archivo_salida archivo_entrada` convertiría el archivo blindado ASCII `archivo_entrada` en un archivo binario `archivo_salida`. |
| `sudo nano` | `nano` es un editor de texto en la terminal. El uso de `sudo` antes de `nano` permite editar archivos con privilegios de superusuario, lo que es útil para modificar archivos que no son propiedad del usuario actual o que requieren permisos elevados para su modificación. | `sudo nano /etc/hosts` abriría el archivo `/etc/hosts` en el editor `nano` con privilegios de superusuario. |
| `systemctl status` | `systemctl` es una herramienta que interactúa y controla systemd, el sistema de inicio y gestor de servicios para sistemas Linux modernos. `status` es una operación que muestra el estado de un servicio o unidad específica. | `systemctl status sshd` mostraría el estado del servicio SSH. |
