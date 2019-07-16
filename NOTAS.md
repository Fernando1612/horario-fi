# Aprendiendo Laravel

```shell
php artisan migrate
```

```shell
php artisan make:controller MateriasController --resource
```

```shell
php artisan make:model Materia -m # -m creates the migration
```

Open a php console

```shell
php artisan tinker
```

Reset all changes (Drop table)

```shell
php artisan migrate:reset
# or
php artisan migrate:fresh
php artisan migrate:fresh --seed
```

How to do seeders

```shell
php artisan make:seeder [NombreSeeder]
```

## Lo que se supone que es básico

Para imprimir en lugar de utilizar `echo` podemos hacer lo sigueinte

```shell
<?= e($user) ?>
```

```shell
php artisan view:clear # limpia el cache de las vistas 
```

