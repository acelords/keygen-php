# Keygen
> A fluent PHP random key generator.

[![Packagist](https://img.shields.io/packagist/v/acelords/keygen.svg)](https://packagist.org/packages/acelords/keygen) [![Packagist](https://img.shields.io/packagist/dt/acelords/keygen.svg)](https://packagist.org/packages/acelords/keygen) [![Packagist](https://img.shields.io/packagist/l/acelords/keygen.svg)]()

Keygen is a PHP package that generates random character sequences known as *keys*. The package ships with built-in key generators for four key types namely: *numeric*, *alphanumeric*, *token* and *byte*. Its implementation effectively combines simplicity and expressiveness.

## Installation

### With Composer
The Keygen package can be installed easily with [Composer] - require the `gladcodes/keygen` package from the command line.

```shell
$ composer require acelords/keygen
```

Alternatively, you can manually add the Keygen package to the `composer.json` file of your project and then run `composer install` from the command line as follows:

```json
{
    "require": {
        "acelords/keygen": "^2.0"
    }
}
```

```shell
$ composer install
```

You can use it in your PHP code like this:

```php
<?php

require __DIR__ . '/vendor/autoload.php';
use Keygen\Keygen;

printf("Your appID is %.0f", Keygen::numeric(12)->generate()); // Your appID is 878234290135
```

## Usage and Documentation
- [Complete Usage Guide]
- [Keygen API Documentation]

## Todos
- Write tests

## License
The Keygen package is covered by the `MIT` License.

[Complete Usage Guide]: <https://github.com/gladchinda/keygen-php/wiki/Usage>
[Keygen API Documentation]: <https://github.com/gladchinda/keygen-php/wiki/Documentation>
