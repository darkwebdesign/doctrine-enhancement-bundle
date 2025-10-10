---
layout: default
title: Getting Started
nav_order: 2
---

# Getting Started

Start here to learn the essentials about developing web applications with the Doctrine Enhancement Pack.

## Installing & Setting up

### Installing via Composer

If you don't have Composer installed in your computer, start by [installing Composer globally](https://getcomposer.org/). Then,
execute the following commands to install the required dependencies:

```bash
composer require darkwebdesign/doctrine-enhancement-bundle
```

```bash
composer install
```

### Enabling the bundle in Symfony

```php
// config/bundles.php
return [
    // ...
    DarkWebDesign\DoctrineEnhancementBundle\DarkWebDesignDoctrineEnhancementBundle::class => ['all' => true],
];
```
