# lumen-data-processor

## Installation

Description:

    $ composer require roba/lumen-data-processor


## Configuration

Inside your `bootstrap/app.php` file, add:

```php
$app->register(craigtapes\DataProcessor\DataProcessorServiceProvider::class);
```

## Run the command

    $ php artisan load:data
