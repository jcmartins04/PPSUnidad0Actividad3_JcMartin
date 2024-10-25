

Para instalar git utilizamos la consola con el comando de linux:

`sudo apt-get install git`

Tras la isntalación de git hemos generado un par de claves para poder usarlas luego mas tarde por ssh al servidor de github.

`ssh-keygen -t ed25519 -C "usuario@dominio.com"`
cambiar usurio y dominio por el que corresponda en cada caso.

![](imagenes/Pasted%20image%2020241025133400.png)

Tras la generación de claves ha de configurarse el archivo "config" de ssh en git para poder conectar los archivos locales con nuestra cuenta a github.
![](imagenes/Pasted%20image%2020241025134404.png)

En identityFile especificaremos la ruta al archivo de claves que hemos creado anteriormente.
Con esta configuración hemos terminado la instalación de git.
Ahora tendremos que vincular nuestro git con la cuenta de github.
Para ello es necesario contar con una cuenta en github.

