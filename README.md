# UPTOPI

## Instrucciones:

#### Script para subir archivos locales a un repositorio remoto.

1. Modificar variables dentro del código:

**DEFAULT_REMOTE_DIRECTORY** --> un directorio por defecto en tu máquina remota en caso de que 
 no pases uno como argumento
**REMOTE_USER** --> el usuario para conectarte remotamente a esa máquina.
**XXX.XXX.X.XXX** --> la Ip de tu máquina remota, recomiendo asignarle una Ip estática, sinó no funcionará.
**HOME_DIRECTORY** --> el directorio **/home/** de tu máquina remota.

 2. Mover el archivo *uptogit* al directorio **/usr/bin** o **/usr/local/bin**
 3. Ir a cualquier directorio y ejecutar el comando:
~~~
uptogit <archivo/directorio_a_subir> <directorio_a_guardar>
~~~
 Éste script sube tanto archivos como directorios.