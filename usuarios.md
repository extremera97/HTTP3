En esta actividad vamos a hacer que un usuario tenga su propio sitio web, para ello debemos:

1. Desde el servidor Apache vamos a *Global configuration*.

![usu0](./images.usu0.PNG)

 2. Nos aparecen varias opciones, pero a nosotros nos interesa *Configura Apache Modules*.

![usu2](./images.usu2.PNG)

3. Tenemos que seleccionar **userdir** y clicar en *Enable Selected Modules*.

![usu1](./images.usu1.PNG)

4. Volvemos al servidor Apache y nos ponemos en la pestaña *Existing virtual hosts*.

![usu52](./images.usu52.PNG)

5. Elegimos el sitio virtual creado por defecto.

![usu3](./images.usu3.PNG)

6. Al principio de la página nos aparecerán varias opciones, nosotros elegimos *Opciones de Documento*.

![usu4](./images.usu4.PNG)

7. Comprobamos que nos aparece la opción **Direcctorio WWW de Usuario** y que está según la imagen a continuación.

![usu5](./images.usu5.PNG)

8. Podemos crear un usuario nuevo, o de un usuario existe, en su directorio /*nome* una carpeta llamada *public_html* y dentro de ella un fichero html llamado *index.html* con la siguiente estructura:

![usudire](./images.usudire.PNG)

9. Una vez creado, en la barra de direcciones ponemos la IP de nuestro servidor seguido de una barra, la virgulilla y por último el nombre del usuario. Por ejemplo:

![usu6](./images.usu6.PNG)
