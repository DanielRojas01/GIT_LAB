# Git Desarrollo colaborativo
Esto es una guia practica para el curso de Git Desarrollo colaborativo. _todos los dias a las 21hs_, el objetivo de la misma es falicitar el entendimiento de los comandos y configuracion de herramientas utilizadas para _el control de versiones_ y  el _desarrollo de una pagina WEB_ desarrollada de forma colaborativa.
## Consfiguracion inicial

* __git init:__ Inicializa un nuevo repositorio en la carpeta/directorio actual.
* __git user.name `username` :__ Define el nombre de usuario para las confirmaciones.
* __git user.email `email` :__ Define el correro de contacto que se muestra en el registro de cambios.

## Gestion de cambios
* __git status:__ Muestra el estado de los archivos comparando el _Working Directory_ con el _Staging Area (INDEX)_
* __git add `file`:__ Agrega al _stagin Area (INDEX)_ los archivos indicados, realizados la _carpeta de codigo (snapshot)_
* __git commit:__ Realiza la configuracion de la captura, almacenando los cambios en un _archivo BLOB (Binary Large Objet)_
* __git log:__ Muestra el historial de confirmaciones de manera decendente, donde los commit se dentifican por su numero de _Hash_