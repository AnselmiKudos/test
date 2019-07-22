<p align="center"><img src="public\img\logo.svg" width="200"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

# oEnergy Asset Management (OAM)

_Aplicación que gestiona todos los PFV de los clientes de oEnergy_

## Comenzando 🚀

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._

### Instalación 🔧
```
git clone https://Alzheimer10@bitbucket.org/tbtfsoft/oam.git

php artisan install

php artisan key:generate

composer run-script post-root-package-install

php artisan migrate

php artisan db:seed

```

## Construido con 🛠️

_las herramientas y Frameworks utilizados para este proyecto_

* [Laravel](https://laravel.com/docs/5.8) - Framework PHP
* [Bootstrap](https://getbootstrap.com/) - Framework CSS - Conjunto de herramientas de código abierto para desarrollar con HTML, CSS y JS.
* [laravel5-repository](https://gitlab.com/ulrichntella/laravel5-repository) - Los repositorios de Laravel 5 se utilizan para abstraer la capa de datos, lo que hace que nuestra aplicación sea más flexible de mantener.
* [Laravel-permission](https://github.com/spatie/laravel-permission) - Este paquete le permite administrar los permisos y roles de los usuarios en una base de datos.
* [laravel-datatables](https://github.com/yajra/laravel-datatables) - Este paquete se crea para manejar los trabajos del lado del servidor de DataTables jQuery Plugin a través de la opción AJAX usando Eloquent ORM, Fluent Query Builder o Collection.
* [laravel-sluggable](https://github.com/spatie/laravel-sluggable) - Este paquete proporciona un trait que generará un slug único al guardar cualquier modelo de Eloquent.

## Licencia 📄

Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo [LICENSE.md](LICENSE.md) para detalles