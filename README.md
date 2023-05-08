# Taller_4_y_5

### Base de datos
Primero se crea la base de datos my_app dentro de esta se crea la tabla users_tbl que contiene el campo used_id como llave primaria y de tipo entero, y los campos user_firstname, user_lastname, user_email, de tipo varchar y el campo de user_password varbinary.

Luego se inserta un nuevo registro en el que se encripta el dato que se ubica en el campo user_passwordy en los campos user_firstname, user_lastname seutiliza el upper para que lo que se dijite en estos campos siempre este en mayusculas.

![image](https://user-images.githubusercontent.com/128266551/236717963-59e99e9a-b6d2-4780-9e03-c65f7b296ad1.png)

### Coneccion BD

En los archivos se encuentran cuatro maneras de conectar con la base de datos 3 de manera local y 1 de manera remota se comprueba que la conexion funciona hacien una consulta que muestre los datos guardados en user_firstname y user_lastname en cada una de las conexiones, cada una contiene un comando por el cual si falla alguno de los requisitos que pide muestre un error de manera que se demuestra que esta fallando.
