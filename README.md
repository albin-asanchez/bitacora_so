
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
