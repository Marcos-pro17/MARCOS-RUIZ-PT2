# Configuración cloud

## Subida de archivos 

Primero de todo buscamos el icono "+"

<img src="archivos.png" alt="">

Vamos donde pone subidas.

<img src="archivos 2.png" alt="">

Seleccionamos el archivo que queremos subir.

<img src="archivo 3.png" alt="">

Ya tendriamos nuestro archivo subido.

<img src="archivos 4.png" alt="">

## Creación de carpetas

Volvemos a ir al icono del "+".

<img src="archivos.png" alt="">

Aqui deberemos fijarnos en la opción que pone "folder".

<img src="carpeta.png" alt="">

Seguidamente nos saldra para crear nuesta carpeta, ponemos el nombre de la carpeta y le damos a crear.

<img src="carpeta 2.png" alt="">

Finalmente ya la tendremos creada.

<img src="carpeta 3.png" alt="">

## Compartir contenido

Para compartir contenido deberemos hacer clic en la carpeta que queremos compartir como sale en la imagen.

<img src="compartir.png" alt="">

Seguidamente tenemos dos opciónes compartir con grupos o compartir con un link público.

<img src="compartir grupos.png" alt="">

<img src="compartir publico.png" alt="">

## Creación de usuarios

Para crear los usuarios deberemos ir a la esquina superior derecha.

<img src="usuarios.png" alt="">

Alli nos abrira un panel donde nos debemos fijar en la pestaña que pone "Users".

<img src="usuarios 2.png" alt="">

Después de entrar en users, en el centro del panel sale unas indicaciones que deberemos rellenar y hacer clic en "create user".

<img src="usuarios 3. " alt="">

Finalmente tendremos creados todos los usuarios que queramos.

<img src="usuarios 4.png" alt="">

## Assignación de roles y permisos 

Primero de todo empezaremos asignando roles, para ello deberemos crear primero los grupos en los que queremos añadir a nuestros usuarios, es decir, nuestros roles.

Para ello primero iremos a la esquina superior izquierda donde pone grupos.

<img src="usuarios 5.png" alt="">

Allí elegiremos el nombre de nuestro rol.

<img src="usuarios 6.png" alt="">

Y finalmente lo crearemos.

<img src="usuarios 7png" alt="">

Para cambiar de rol a cada uno de los usuarios nos vamos a ellos y en la pestaña donde pone admin hacemos clic y los cambiamos.

<img src="usuarios 8.png" alt="">

Ahora para dar permisos a cada uno de ellos en documentos 

Vamos a la pagina principal donde tenemos todo lo nuestro.

<img src="permisos.png" alt="">

Seguidamente hacemos lo mismo que si fueramos a compartir el documento o la carpeta.

<img src="permisos 2.png" alt="">

Nos vamos a la parte del sharing

<img src="permisos 3.png" alt="">

Cuando ya estemos allí hacemos clic en la parte de "users and groups".

<img src="permisos 4.png" alt="">

Allí añadimos los roles previamente creados.

<img src="permisos 5.png" alt="">

Despues de añadir el rol hacemos clic en la rueda que hay y se nos desplegara un panel.

<img src="permisos 6.png" alt="">

Ahi podremos elegir nuestros permisos para cada rol.

<img src="permisos 7.png" alt="">

Al editor, le he puesto que pueda gestionar el documento, pero que no pueda borrar ni crear y al visualizador, le he quitado todos los permisos para que solo pueda ver.

<img src="permisos 8.png" alt="">

## Organizar archivos y carpetas 

Owncloud tiene diferentes metodos de organización.

Yo he encontrado:

  - Como mover archivos
  - Como poner en favoritos
  - Camviar el nombre para separarlos por orden alfabetico

### Mover archivos

Primero deberemos poner el raton en el archivo que queremos mover.

<img src="mover.png" alt="">

Seguidamente arrastramos con el clic derecho presionado hacia la carpeta donde lo queremos guardar. Así deberia quedar.

<img src="moverlos 2.png" alt="">

### Poner en favoritos

Para poner en favoritos es muy sencillo, nos colocamos encima del archivo que queremos poner en favoritos.

<img src="favoritos.png" alt="">

Cuando hagamos eso a la izquierda del documento o carpeta saldra una estrella.

<img src="favoritos 2.png" alt="">

hacemos clic en la estrella y ya podremos ver esos archivos o carpetas en la sección de favoritos del panel izquierdo.

<img src="favoritos 3.png" alt="">

### Cambiar nombre para ordenar de manera alfabética

Vamos a nuestros archivos

<img src="cambiar nombre.png" alt="">

Hacemos clic en los tres puntos que tiene cada uno de nuestros archivos.

<img src="cambiar nombre 2.png" alt="">

Ahora nos saldra un panel, deberemos fijarnos en el botón que pone "rename".

<img src="cambiar nombre 3.png" alt="">

Ahi cambiamos el nombre de manera que nos canvenga, teniendo en cuenta que ordenar de manera alfabetica.

<img src="cambiar nombre 4.png" alt="">


## Políticas de seguridad

Para configurar las políticas de seguridad deberemos ir otra vez a la esquina superior derecha.

<img src="seguiridad.png" alt="">

Ahora nos vamos a el btón de "preferencias"

<img src="seguridad 2.png" alt="">

Aqui se nos abrirá un panel, dberemos irnos a "Sharing".

<img src="seguridad 3.png" alt="">

Se nos abrirá este panel.

<img src="seguridad 4.png" alt="">

Aqui elegimos lo que nos venga mejor, yo pondre que se establezca una fecha de caducidad para las comparticionesde grupo y usuarios, voy a quitar que acepte automaticamente los nuevos compartidos de usuarios y también añadire una restricción a los usuarios para que solo puedan compartir con los grupos en los cuales són miembros.

<img src="seguridad 5.png" alt="">

## Configurar el accéso desde otra maquina 

Para que se pueda hacceder desde otra maquina primero deberemos saber la IP local 

<img src="acceso.png" alt="">

Seguidmanete tendremos que saber si apache2 esta encendido

<img src="acceso 2.png" alt="">

Ahora entramos en archivo donde esta la configuración y los dominions.

<img src="acceso 3.png" alt="">

Donde pone "trusted_domains" añadimos una linea debajo de 0 => 'localhost' y ponemos la IP local, guardamos y cerramos.

<img src="acceso 4.png" alt="">

Ahora ya deberia funcionar desde una maquina de la misma red.





















