Crear Modelo,Migracion,Seeder y Controlador: php artisan make:model Articulo -mscr

protected $fillable = [
	'name',
	'email',			Restringe los datos que pueden ser modificados.
	'password',
]

Crear Migracion: php artisan make:migration create_articulos_table

Correr Migracion: php artisan migrate

Crear Controlador: php artisan make:controller ArticuloController --resource
invocar al modelo en el controlador

Resetear Migracion: php artisan migrate:fresh --seed

Rellenar Datos: php artisan db:seed --class=nombreDelSeed

Crear rama: git checkout -b NAME

Agregar Cambios: git add .

Agregar correo: git config --global user.email "correo@gmail.com"

Agregar username: git config --global user.name "username"

Crear commit: git commit -m 'especificacion'

Subir cambios: git push origin NAMEPROBLEM

Bajar cambios: git pull origin NAMERAMA