# dotEnv
.env parser plugin for Core-PHP applications

## Installation

Require this package with composer:

```shell
composer require lionrajkumar/dotenv
```

## Usage

```php
require 'vendor/autoload.php';

$env = new \lionrajkumar\DotEnv(__DIR__ . "/.env");
$env->load();
```

## Quick Examples

Please refer to our extensive [Wiki documentation](https://github.com/lionrajkumar/dotEnv/wiki) for more information.

## Support

For answers, you may not find in the Wiki, avoid posting issues. Feel free to ask for support on lionrajkumar.com

## License

This package is licensed under the [MIT License](https://github.com/lionrajkumar/dotEnv/blob/main/LICENSE).


[Ref](https://www.w3resource.com/php/composer/create-publish-and-use-your-first-composer-package.php)