Para registrarse en github deberemos realizar los pasos que se nos indiquen en la web: https://github.com 
Posteriormente se procederá a añadir la clave ssh pública que generamos anteriormente por consola.

![](imagenes/Pasted%20image%2020241025135038.png)
Se accede a través de menú de configuración "Settings" > Añadir Clave SSh.


![](imagenes/Pasted%20image%2020241025135048.png)
Se añade la llave y se pega el contenido de la captura. Se ha pixelado por seguridad.
Comprobamos desde la consola mediante `ssh github.com`donde nos muestra que nos hemos autenticado correctamente con nuestro usuario.


![](imagenes/Pasted%20image%2020241025135113.png)
Creamos posteriormente un nuevo repositorio con el nombre que se nos ha indicado: 

![](imagenes/Pasted%20image%2020241025135152.png)

Y posteriormente procederemos a clonar el repositorio a nuestro ordenador.
con el comando `git clone`pegando directamente la dirección del repositorio desde el botón de la aplicación denominado "SSH". 
![](imagenes/Pasted%20image%2020241025135206.png)
Una vez clonado el repositorio podremos comenzar a trabajar localmente en el. Posteriormente, todos los cambios que vayamos haciendo se reflejaran en el repositorio remoto tras ejecutar un commit y un push.

