# PokechallengeProduction
Este aplicativo web te permitirá buscar a tus pokemon´s favoritos ya sea por su número o su nombre, así mismo,  podrás agregarlos a tu cuenta.

## INSTRUCTIVO
Para instalar el proyecto debera tener instalado Docker

1° Debera clonar el repositorio  desdel siguiente link: 
https://github.com/roduriel/PokechallengeProduction.git
con el comando git clone

2° Desde la tarminal, buscar la carpeta donde se guardo
la el archivo y situarse sobre ella.

3° Se deberá ingresar el siguiente comando: 
docker-compose up -d.

4° una vez que haya finalizado el proceso de instalacion
del contenedor, se mostrará en la misma terminal, cuando 
este listo para que accedamos por nuestro navegador.

5° Correremos el siguiente comando:
docker ps
para que podamos observar el id del contenedor en donde
estara funcionando el proyecto.

6° Ejecutamos el comando: 
docker excec -it <idContenedor> /bin/bash
 
7° Posteriormente corremos el comando 
cd ../ 
para regresar un directorio atras.

8° Finalmente podemos correr el comando: php artisan migrate
para correr nuestras migraciones de laravel.

9° Desde el navegador podemos ingresar a la direccion:
localhost:8200 y ya podremos buscar a nuestros pokemon´s
favoritos.
