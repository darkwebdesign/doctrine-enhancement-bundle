# Doctrine Enhancement Bundle

[![Latest Stable Version](https://poser.pugx.org/darkwebdesign/doctrine-enhancement-bundle/v/stable?format=flat)](https://packagist.org/packages/darkwebdesign/doctrine-enhancement-bundle)
[![Total Downloads](https://poser.pugx.org/darkwebdesign/doctrine-enhancement-bundle/downloads?format=flat)](https://packagist.org/packages/darkwebdesign/doctrine-enhancement-bundle)
[![License](https://poser.pugx.org/darkwebdesign/doctrine-enhancement-bundle/license?format=flat)](https://packagist.org/packages/darkwebdesign/doctrine-enhancement-bundle)

[![Build Status](https://travis-ci.org/darkwebdesign/doctrine-enhancement-bundle.svg?branch=2.7)](https://travis-ci.org/darkwebdesign/doctrine-enhancement-bundle?branch=2.7)
[![PHP Version](https://img.shields.io/badge/php-7.1%2B-777BB3.svg)](https://php.net/)
[![Symfony Version](https://img.shields.io/badge/symfony-4.0%2B-93C74B.svg)](https://symfony.com/)
[![Doctrine Version](https://img.shields.io/badge/doctrine-2.7-2E6BC8.svg)](http://www.doctrine-project.org/)

Doctrine Enhancement Bundle conveniently wraps the [Doctrine Enhancement Pack](https://github.com/darkwebdesign/doctrine-enhancement-pack) with a Symfony Bundle that you can use
in your Symfony applications.

## Installing via Composer

```bash
composer require darkwebdesign/doctrine-enhancement-bundle
```

```bash
composer install
```

## Enabling the bundle in Symfony

```php
// config/bundles.php
return [
    // ...
    DarkWebDesign\DoctrineEnhancementBundle\DarkWebDesignDoctrineEnhancementBundle::class => ['all' => true],
];
```


## License

Doctrine Enhancement Bundle is licensed under the MIT License - see the `LICENSE` file for details.
