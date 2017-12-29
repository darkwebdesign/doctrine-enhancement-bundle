# Doctrine Enhancement Bundle

[![Latest Stable Version](https://poser.pugx.org/darkwebdesign/doctrine-enhancement-bundle/v/stable?format=flat)](https://packagist.org/packages/darkwebdesign/doctrine-enhancement-bundle)
[![Total Downloads](https://poser.pugx.org/darkwebdesign/doctrine-enhancement-bundle/downloads?format=flat)](https://packagist.org/packages/darkwebdesign/doctrine-enhancement-bundle)
[![License](https://poser.pugx.org/darkwebdesign/doctrine-enhancement-bundle/license?format=flat)](https://packagist.org/packages/darkwebdesign/doctrine-enhancement-bundle)

[![Build Status](https://travis-ci.org/darkwebdesign/doctrine-enhancement-bundle.svg?branch=2.8)](https://travis-ci.org/darkwebdesign/doctrine-enhancement-bundle?branch=2.8)
[![Minimum PHP Version](https://img.shields.io/badge/php-%3E%3D%205.3-blue.svg)](https://php.net/)
[![Minimum Symfony Version](https://img.shields.io/badge/symfony-%3E%3D%202.3-green.svg)](https://symfony.com/)

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
// app/AppKernel.php
public function registerBundles()
{
    $bundles = array(
        // ...
        new DarkWebDesign\DoctrineEnhancementBundle\DarkWebDesignDoctrineEnhancementBundle(),
    );

    // ...
}
```


## License

Doctrine Enhancement Bundle is licensed under the MIT License - see the `LICENSE` file for details.
