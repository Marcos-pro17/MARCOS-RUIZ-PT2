# Isard VDI
Para comenzar la instalación utilizaremos una maquina virtual llamada Isard VDI.

Primero buscamos el sitio web en internet o en nuestro navegador.

<img src="Isard.png" alt="">

Entramos en el link marcado.

<img src="2025-05-06_13-19.png" alt="">

Iniciamos sesión con nuestro Usuario y contraseña 

<img src="usuario y contraseña isard.png" alt="">

Creamos un escritorio nuevo.

<img src="escritorio.png" alt="">

Seleccionamos el Ubuntu desktop y ponemos nombre a nuestro escritorio.

<img src="escritorio 2.png" alt="">

Al tener nuestro escritorio creado, entramos en los 3 puntos que salen para configurar el escritorio. 

<img src="escritorio 3.png" alt="">

Y desde este panel añadimos: CPUS, memoria y dejamos los videos tal y como estan.

<img src="escritorio 4.png" alt="">

# Owncloud

1. Actualización de la máquina
   
<img src="sudo apt update.png" alt="">

<img src="sudo upgrade.png" alt="">

3. Instalación del servidor web apache2
   
<img src="sudo install apache.png" alt="">

5. Instalación del servidor de bases de datos mysql-server
   
<img src="sudo install mysql.png" alt="">

6. Instalación de algunas librerías de PHP, el lenguaje principal que utilizan las aplicaciones
   
<img src="librerias 1.png" alt="">

<img src="librias 2.png" alt="">

7. Reiniciamos el servidor apache2
   
<img src="reset apache.png" alt="">

## Configuración de MySQL

Accedemos a la consola de MySQL

<img src="consola msql.png" alt=""> 

Creación de la base de datos

<img src="database.png" alt=""> 

Creación de un usuario

<img src="usuario database.png" alt=""> 

Conceder privilegios al usuario

<img src="privilegios.png" alt=""> 

Salir de la base de datos

<img src="exit.png" alt=""> 

Probar la conexión a la base de datos

<img src="comprobación mysql.png" alt=""> 

<img src="comprobación mysql 2.png" alt=""> 


# Descargamos los archivos de la aplicación web
En este punto deberemos descargar el archivo donde esta la cloud: https://download.nextcloud.com/server/releases/latest.zip .

Después de descargar seguimos estos pasos.

- Vamos al directorio /var/www/html.
  <img src="cd.png" alt="">

- Copiamos la carpeta descargas y el archivo descargado en /var/www/html y descomprimimos el archivo.

  <img src="cp.png" alt="">

  <img src="unzip.png" alt="">

- Eliminamos la carpeta creada al descomprimir

  <img src="eliminar carpeta.png" alt="">

- Eliminamos el archivo index.html por defecto de Apache2

  <img src="eliminar index.png" alt="">

# Aplicamos permisos a nuestra aplicación web

<img src="permisos.png" alt="">

Accedemos al navegador para comprobar que todo funciona

Introduce la dirección http://localhost en tu navegador web y continúa con la configuración de la aplicación

<img src="locahost.png" alt="">

<img src="cloud.png" alt="">

Para iniciar sesión ponemos estos datos:

Usuario: usuario
Contraseña: password
Base de datos: bbdd
Dominio: localhost
















