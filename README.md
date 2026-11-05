# README #

  ## Cómo he desplegado el proyecto

   1. Fork de `mpgprofe/miniblog` y clone por SSH.
   2. `composer install`, `php bin/console create-schema` y `php bin/console app:create-user admin "Administrador"`.
   3. Servidor de pruebas con `php -S localhost:8000 -t public`.
