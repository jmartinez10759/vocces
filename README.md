#### INSTALACIÓN

 - Clonar el repositorio.
 - Crear el archivo `.env` (ejemplo en `.env.example`).
 - Instalar las dependencias `composer install`.
 - Ejecutar las migraciones `php artisan migrate`.
 - Ejecutar `php artisan key:generate`.
 - Validar instalación con los test `php artisan test`.
----

#### REQUISISTOS

 - PHP 7.3
 - Mysql o MariaDB

----

#### EJERCICIOS

 - Agregar las propiedades `email` y `address` a las compañías.
 - Crear un nuevo caso de uso para actualizar el estado de una compañía de `inactive` a `active`.
 - Crear un nuevo endpoint de API que actualice el estado usando el caso de uso del punto anterior.
 - Crear nuevo caso de uso que liste todas las compañías.
 - Crear un nuevo endpoint de API que liste las compañías en base al caso de uso del punto anterior.
 - Los test deben pasar después de realizar los cambios.
 - Opcional: Implementa cualquier otra entidad de dominio.


#### ENTREGAR PRUEBA

 - Hacer fork del repositorio.
 - Realizar los ejercicios.
 - Solicitar un merge request al repositorio original.
