Asegúrese de que todos los archivos sean propiedad del grupo y usuario de Apache. En Ubuntu es el grupo www-data y el usuario

sudo chown -R www-data:www-data /var/www/html

A continuación, habilita a todos los miembros del grupo www-data para leer y escribir archivos

sudo chmod -R g+rw /var/www/html

La función php mkdir()ahora debería funcionar sin devolver errores