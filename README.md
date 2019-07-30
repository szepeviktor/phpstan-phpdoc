# PHPDoc and typehint checks only for PHPStan

[![CircleCI](https://circleci.com/gh/szepeviktor/phpstan-phpdoc.svg?style=svg)](https://circleci.com/gh/szepeviktor/phpstan-phpdoc) [![Packagist](https://img.shields.io/packagist/v/szepeviktor/phpstan-phpdoc.svg?color=239922&style=popout)](https://packagist.org/packages/szepeviktor/phpstan-phpdoc)

This [PHPStan](https://github.com/phpstan/phpstan) extension
checks only PHPDoc and typehint related errors in your code.

## Installation

1. Do not set rule level (`--level`)
1. Require this package in [Composer](https://getcomposer.org/):

```
composer require --dev szepeviktor/phpstan-phpdoc
```

If you also install [phpstan/extension-installer](https://github.com/phpstan/extension-installer)
then you're all set.

<details>
<summary>Manual installation</summary>

If you don't want to use `phpstan/extension-installer`,
include extension.neon in your project's PHPStan config:

```
includes:
    - vendor/szepeviktor/phpstan-phpdoc/extension.neon
```

</details>
