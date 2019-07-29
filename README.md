# PHPDoc and typehint checks only for PHPStan

[![CircleCI](https://circleci.com/gh/szepeviktor/phpstan-phpdoc.svg?style=svg)](https://circleci.com/gh/szepeviktor/phpstan-phpdoc) [![Packagist](https://img.shields.io/packagist/v/szepeviktor/phpstan-wordpress.svg?color=239922&style=popout)](https://packagist.org/packages/szepeviktor/phpstan-phpdoc)

[PHPStan](https://github.com/phpstan/phpstan)

### Usage

1. Install `szepeviktor/phpstan-phpdoc` Composer package.
1. Do not set rule level (`--level`)
1. Include its configuration:

```yaml
includes:
    - vendor/szepeviktor/phpstan-phpdoc/extension.neon
```

### What this extension does

Checks only PHPDoc and typehint related errors in your code.
