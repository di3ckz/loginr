En terminal dentro de la  carpeta del proyecto se instala la libreria
1. composer require laravel/breeze --dev
Se ejecutae este comando
2. php artisan breeze:install
Se ejecutan los siguientes comandos
-npm install && npm run dev

Se importa la base de datos a mysql

Se introduce el comando  php artisan serve, damos click en la  direccion  que aparece
donde encontraremos un register y un login en la parte superior derecha.

nota: Quitar el 1. 2. 3. 4. 5. a los documentos que vienen en la carpeta raiz, ya que en uno de ellos va el .env y no se querian subir si no le ponia algo antes  del .
Nota,  si no  funciona el recaptcha se hace lo siguiente:
***Entramos a la pagina de google.com/recaptcha/admin/create
se coloca el nombre de  la etiqueta
Se selecciona recaptchaV2
En el dominio se coloca 127.0.0.1
Se coloca un correo
Se aceptan condiciones y se da click en enviar
Se sustituye el secretkey y sitekey por  los que  aparecen  en  la  siguiente  ventana
Sería todo.
