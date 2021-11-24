
# Laravel Datatables Ajax

Mini project to demonstrate Laravel Yajra Datatables in Ajax

## Version
```bash
Laravel v8.73.2 (PHP v8.0.0)
```
## Installation

Install my-project with npm

```bash
npm install my-project
cd my-project
Run: composer install
php artisan key:generate
Set .env database
CREATE DATABASE yajra_datatables;

$ composer require yajra/laravel-datatables-oracle:"~9.0"
goto: config>app.php
'providers' => [
    Yajra\DataTables\DataTablesServiceProvider::class,
]

'aliases' => [
    'DataTables' => Yajra\DataTables\Facades\DataTables::class,
]
php artisan vendor:publish --provider="Yajra\DataTables\DataTablesServiceProvider"
```

## Requirements
```bash
Composer
Nodejs - for npm installation
Yajra datatables - https://github.com/yajra/laravel-datatables

<!-- JQUERY LATEST 3.6.0 -->
<script src="https://code.jquery.com/jquery-3.6.0.js" integrity="sha256-H+K7U5CnXl1h5ywQfKtSj8PCmoN9aaq30gDh27Xc0jk=" crossorigin="anonymous"></script>

<!-- Boostrap 5 -->
<!-- Latest compiled and minified CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.2/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Latest compiled JavaScript -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.2/dist/js/bootstrap.bundle.min.js"></script>
```
<ul>
    <li>
        <a href="https://cdn.datatables.net/1.11.3/js/jquery.dataTables.min.js">https://cdn.datatables.net/1.11.3/js/jquery.dataTables.min.js</a>
    </li>
    <li>
        <a href="https://cdn.datatables.net/buttons/2.0.1/js/dataTables.buttons.min.js">https://cdn.datatables.net/buttons/2.0.1/js/dataTables.buttons.min.js</a>
    </li>
    <li>
        <a href="https://cdnjs.cloudflare.com/ajax/libs/jszip/3.1.3/jszip.min.js">https://cdnjs.cloudflare.com/ajax/libs/jszip/3.1.3/jszip.min.js</a>
    </li>
    <li>
        <a href="https://cdnjs.cloudflare.com/ajax/libs/pdfmake/0.1.53/pdfmake.min.js">https://cdnjs.cloudflare.com/ajax/libs/pdfmake/0.1.53/pdfmake.min.js</a>
    </li>
    <li>
        <a href="https://cdnjs.cloudflare.com/ajax/libs/pdfmake/0.1.53/vfs_fonts.js">https://cdnjs.cloudflare.com/ajax/libs/pdfmake/0.1.53/vfs_fonts.js</a>
    </li>
    <li>
        <a href="https://cdn.datatables.net/buttons/2.0.1/js/buttons.html5.min.js">https://cdn.datatables.net/buttons/2.0.1/js/buttons.html5.min.js</a>
    </li>
    <li>
        <a href="https://cdn.datatables.net/buttons/2.0.1/js/buttons.print.min.js">https://cdn.datatables.net/buttons/2.0.1/js/buttons.print.min.js</a>
    </li>
</ul>

