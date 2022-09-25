# Git Desarrollo colaborativo
Esto es una guia practica para el curso de Git Desarrollo colaborativo. _todos los dias a las 21hs_, el objetivo de la misma es falicitar el entendimiento de los comandos y configuracion de herramientas utilizadas para _el control de versiones_ y  el _desarrollo de una pagina WEB_ desarrollada de forma colaborativa.
## Consfiguracion inicial

* __git init:__ Inicializa un nuevo repositorio en la carpeta/directorio actual.
* __git user.name `username` :__ Define el nombre de usuario para las confirmaciones.
* __git user.email `email` :__ Define el correro de contacto que se muestra en el registro de cambios.
* __git remote rename `nombre del remoto` nuevo `nombre`:__ Cambia el nombre del remoto.
## Gestion de cambios
* __git status:__ Muestra el estado de los archivos comparando el _Working Directory_ con el _Staging Area (INDEX)_
* __git add `file`:__ Agrega al _stagin Area (INDEX)_ los archivos indicados, realizados la _carpeta de codigo (snapshot)_
* __git commit:__ Realiza la configuracion de la captura, almacenando los cambios en un _archivo BLOB (Binary Large Objet)_
* __git log:__ Muestra el historial de confirmaciones de manera decendente, donde los commit se dentifican por su numero de _Hash_

## Repositorio Remotos

* __git remote -v:__ Muestra los repositorios remtos gestionados, incluyendo la url de los mismos.
* __git remote add `alias` `url`:__ Agrega una nueva direccion remota donde podemos subir los cambios.
* __git remote rename `old_name` `new_name`:__ Cambia el nombre de algun repositorio remoto.
* __git remote set-url `alias` `url`:__ Modifica la url del repositorio remoto seleccionado.
* __git remote remove `alias`:__ Elimina el repositorio remoto de la lista de direcciones remotas.

## Sincronizacion de Cambios

* __git clone `url`:__ Descarga en una carpeta el contenido de un repositorio remoto.
* __git push `remote` `branch`:__ Envia el historial de confirmaciones al repositorio remoto.
* __git fetch `remote`:__ Descarga el historial de confirmaciones del repositorio remoto.
* __git pull `remote` `branch`:__ Descarga e integra los cambios del repositorio remoto.