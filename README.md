# Env Manager extension for laravel-admin


## Screenshot

![screenshot](https://user-images.githubusercontent.com/2421068/47560963-7ea0a800-d94c-11e8-95d9-57c6fee1d9bb.png)

## Requirements

* open-admin >= 2.0.1

## Installation

```bash
composer require dedermus/env-manager

# If you want to add a link entry in the left menu, use the following command to import
php artisan admin:import env-manager
```

## Configurations

Add `extensions` option in your `config/admin.php` configuration file:

```php
'extensions' => [
    'env-manager' => [
        // If the value is set to false, this extension will be disabled
        'enable' => true
    ]
]
```

## Usage

Open http://your-host/admin/env-manager

And you can find the `.env` variables.


## More resources

[Awesome open-admin-core](https://github.com/dedermus/open-admin-core)


## License

Licensed under [The MIT License (MIT)](LICENSE).

