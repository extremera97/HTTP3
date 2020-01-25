Antes de empezar a crear sitios virtuales y a discriminarlos sin saber exactamente lo que estamos haciendo debemos saber un par de cosas antes de empezar. Como por ejemplo: **¿Cuátos sitios virtuales puedo tener en mi servidor web?**

En mi servidor web puedo tener cuantos sitios virtuales siempre que su nombre DNS, puerto o IP sean distintas. Por eso discriminarlas es importante.

Al discriminarlas lo que hacemos es diferenciarla, es decir, para que no haya confusiones a la hora de acceder a ellos lo que hacemos es nombrarlas por puerto, ip o nombre dns.

En esta práctica aprenderás como crear sitios virtuales y discriminarlas.

Primero, vamos a empezar con la discriminación por puerto:

1. Para empezar, desde nuestro servidor Apache tenemos la ventana "Create Virtual Host", que nos muestra una serie de opciones marcadas por defecto:

[discripuerto]

2. Una de las opciones que debemos cambiar es la de Puerto, yo he elegido el 8000.

[discripuerto2]

3. Ahora debemos elegir la carpeta que queremos que sea para Raíz para Documentos. Para ello crearemos una carpeta en el directorio raíz para nuestro servidor, que la llamaremos servidor*TUNOMBRE*

Dentro de ella crearemos otra carpeta llamada **puerto**, y dentro de esta un documento html llamado *index.html* con la siquiente esctructura:

[discripuerto3]

4. Ahora en Raiz para Documentos debemos escribir la ruta de nuestra carpeta, que debería ser /servidor*TUNOMBRE*/puerto.

[discripuerto4]

Lo que estamos haciendo en este paso es indicarle a nuestro sitio virtual que queremos que muestre el contenido de la carpeta en el sitio. 

[falta la captura del sitio]

Ahora que ya hemos creado un sitio virtual y hemos comprobado que funciona, vamos a crear otro sitio virtual que vamos a discriminar por IP.

1. Desde la ventana de "Create Virtual Host" dejaremos todas las opciones por defecto excepto la casilla de **Manejar conexiones para direccionar** y escribiremos una IP dentro de nuestro rango.

[discriip]

1. Para discriminar por puerto también debemos crear una carpeta dentro de nuestra carpeta de servidor llamada ip.

Dentro de esta crearemos otro documento html llamado *index.html*
