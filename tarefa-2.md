# Tarefa 2



> ----------------------------------------



# MariaDB


## Instalación de MariaDB


Empezamos abriendo una terminal.

![FOTO1](./img/Foto1.PNG)

Vamos a la página de MariaDB y seleccionamos nuestra versión de Ubuntu. Lo cual nos enseña los pasos que debemos de seguir.

![FOTO1A](./img/Foto1A.PNG)

Escribimos el primer paso que nos pone en la página: `sudo apt-get install software-properties-common`

![FOTO1B](./img/Foto1B.PNG)

Escribimos el siquiente paso: `sudo apt-key adv --fetch-keys 'https://mariadb.org/mariadb_release_signing_key.asc'`

![FOTO1C](./img/Foto1C.PNG)

Y escribimos el último paso de esta parte: `sudo add-apt-repository 'deb [arch=amd64,arm64,ppc64el] http://mariadb.mirror.triple-it.nl/repo/10.4/ubuntu bionic main'`

![FOTO1D](./img/Foto1D.PNG)

Después escribimos sudo apt-get update y dejamos que se actualize.

![FOTO2](./img/Foto2.PNG)

Una vez actualizado escribimos sudo apt install mariadb-server (Le damos a Y en si queremos continuar.)

![FOTO3](./img/Foto3.PNG)

Cuando se haya instalado, usamos sudo mysql para iniciar el monitor de MariaDB.

![FOTO 4](./img/Foto4.PNG)

Escribir \h (o también \?) nos abre una lista con los comandos que se pueden usar.

![FOTO 5](./img/Foto5.PNG)

Y una vez comprobado que funciona, escribimos exit para salir y MariaDB se despide.

![FOTO 6](./img/Foto6.PNG)



> ----------------------------------------