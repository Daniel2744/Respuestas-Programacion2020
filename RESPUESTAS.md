# *PROGRAMACIÓN 2020*
## Cuestionario
+ ¿Qué es git?
>Git en un sistema de control de versiones (controla y administra las distintas versiones de un programa)
+ ¿Por qué queremos utilizar git?
>Lo queremos utilizar porque te genera un listado de los cambios que se realizan con el pasar del tiempo en el programa, lo que resulta muy útil al querer visualizar el código por ejemplo de dos versiones anteriores a la actual que se está trabajando
Te permite trabajar con un repositorio de código y múltiples desarrolladores van a poder modificar ese código pero todos los desarrolladores tendrán una copia local de ese código
Te permite realizar snapshots, (es como tomarle fotos al codigo y luego se puede modificar ) luego se pueden volver a ver para copiarlos, modificarlos, etc.te permite realizar gardados de tu aplicación en cualquier momento, por ejemplo en cada cambio de version
+ ¿Qué es el bash que instala git?
>El bash que istala git es una consola donde podremos ejecutar los comandos que agreguemos a nuestro programa
+ Describa los estados (working directory, staging area, repository)  
>**Working directory:** Es donde trabajas con todos tus archivos  
**Staging área:** Donde se agragan los archivos que se preparan para el guardado (versión 1, versión 2, etc.)  
**Repository:** Es la plataforma a donde se subirán los comandos guardados del proyecto
+ Describa el flujo para crear un nuevo repositorio git.
>Para crear un repositorio git, debes ir a la parte superior en la seccione de repositorios.
Seleccionamos nuevo, lo que nos direcciona a la creación de un nuevo repositorio.
Le colocamos un nombre, también se le podrá poner una descripción del proyecto. Elegimos si lo queremos público o privado 
+ Describa el flujo para agregar un archivo simple al repositorio.
>Para agregar un archivo en al repositorio se debe escribir en el bash git remote add origin con la dirección de la página a la que se subirá el proyecto, luego escribir git push -u origin master. Luego de esto te pedirá que verifiques tu ususario y contraseña de github para así poder subir el código a tu repositorio.
+ Describa el flujo para cambiar el archivo agregado y guardar los cambios en el repositorio.
>Para cambiar un archivo agregado se debe hacer click al archivo que se desea editar, luego se hace click en el lápiz a su derecha para empezar a editarlo. Una vez editado se va al fondo de la página y se preciona Commit changes para guardar los cambios efectuados.
+ ¿Cómo hago para ignorar un archivo o carpeta?
>Para ignorar un archivo o carpeta se crea un archivo con el nombre .gitignore donde se le agregara el nombre del archivo o carpeta que se desea ignorar
+ Explique qué es un branch. Dé un pequeño ejemplo de cómo haría uno.
>Branch es el apuntador a la rama en la que se encuentra actualmente, ya sea master o una rama que se haya creado después. Git branch crea una nueva rama pero no te direcciona a ella. Para ver cada rama tiene que escribir el comando git log.
+ ¿Qué hago con "git add ."?
>Con git add sirve para pasar todos los archivos de working directory a staging area, sin necesidad de ir agregando uno por uno.
+ ¿Cómo cambiamos de un branch a otro?
>Primero se debe crear una versión alternativa escribiendo git branch y el nombre que se desea que tenga esta versión alternativa.
Para cambiar de uno a otro solo basta con escribir git checkout y el nombre de la versión, ya sea master o alguna versión alternativa que hayamos creado.
+ Investigue qué es Markdown y responda todas las preguntas anteriores en este lenguaje 
>Markdown es un lenguaje de marcado que facilita la aplicación de formato a un texto empleando una serie de caracteres de una forma especial.
