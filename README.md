# ventas-pc
prueba técnica

###Install
1.- Descargar version 1.1 de el framework de Yii en yiiframework.com en el directorio accesible de el server.
2.- Descargar proyecto en la ruta del server (htdocs)
3.- Crear la base de datos en mysql con un nombre "svc"
4.- Ir a la ruta /protected/data/ventas-pc.sql y ejecutar el contenido dentro de la base de datos creada
5.- Una vez que se creó la base de datos configurar el password, nombre de la base de datos y el host en el archivo de configuración  que se encuentra en la ruta protected/config/database.php

~~~
return array(
	'connectionString' => 'mysql:host=localhost;dbname=dbname',
	'emulatePrepare' => true,
	'username' => 'root',
	'password' => 'password',
	'charset' => 'utf8',	
);
~~~

6.- Entrar a la terminal ubicarte en la carpeta de la aplicacion al nivel protected 
	- En windows si no existe la variable path php, teclea en la terminal  la ruta a php "path/to/php.exe" yiic migrate
	- En linux ejecutar el comando php yiic migrate
	- Confimar aplicacion de la migracion tecleando la letra y enter.
	
7.- Acceder a la aplicación desde el navegador "http://myserver/folder_name/".

