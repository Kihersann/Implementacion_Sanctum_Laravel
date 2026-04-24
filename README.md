# Biblioteca Laravel

Aplicación web desarrollada con Laravel para la gestión de una biblioteca: libros, autores, préstamos y usuarios.

## Características

- Registro y autenticación de usuarios
- CRUD de libros y autores
- Gestión de préstamos con fechas de devolución
- Sistema de categorías y búsqueda
- Panel de administración

## Tecnologías

- **Backend:** Laravel 11, PHP 8.2
- **Base de datos:** MySQL
- **ORM:** Eloquent
- **Migraciones:** Schema Builder de Laravel

## Instalación

```bash
git clone https://github.com/tu-usuario/tu-repo.git
cd tu-repo

composer install
cp .env.example .env
php artisan key:generate

# Configura tu base de datos en .env, luego:
php artisan migrate
php artisan db:seed

php artisan serve
```

