Json-Server
===========

Servidor REST que cuenta con una base de datos en formato JSON, que nos permitira trabajar los mockups para nuestras aplicaciones Web.

Requerimientos
--------------

* docker-machine
* docker
* docker-compose

Kitematic te instala todas esas herramientas:

https://docs.docker.com/toolbox/overview/

Primeros pasos
--------------

* Clonar el repositorio
~~~
git clone https://github.com/dev-lusaja/JsonServer-Docker.git
~~~

* Ingresar al directorio
~~~
cd virtuales/JsonServer-Docker/docker/
~~~

* Ejecutar la construcción del docker-compose.yml
~~~
docker-compose build
~~~

* Encender el contenedor
~~~
docker-compose up
~~~

* Probar la conexión al seridor local
~~~
http://192.168.99.100:3000/personas
http://192.168.99.100:3000/emails
http://192.168.99.100:3000/direcciones
~~~

PD: Cuando utilizas docker, este te asigna una ip para la maquina virtual que por defecto es: 192.168.99.100