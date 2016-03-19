# Menu Bundle for GravityCMS

This bundle integrates configurable menus into GravityCMS by using the 
[KNP Menu](https://github.com/KnpLabs/KnpMenu) implementation.

## Installation

### Composer
```bash
composer require gravity-cms/menu-bundle
```

### AppKernel.php
```php
$bundles = [
    // ...
    new Knp\Bundle\MenuBundle\KnpMenuBundle(),
    new Gravity\MenuBundle\GravityMenuBundle(),
]
```