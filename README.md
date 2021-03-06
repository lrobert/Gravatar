# Gravatar
[![Latest Stable Version](https://poser.pugx.org/lrobert/gravatar/v/stable.svg)](https://packagist.org/packages/lrobert/gravatar) [![Total Downloads](https://poser.pugx.org/lrobert/gravatar/downloads.svg)](https://packagist.org/packages/lrobert/gravatar) [![Latest Unstable Version](https://poser.pugx.org/lrobert/gravatar/v/unstable.svg)](https://packagist.org/packages/lrobert/gravatar) [![License](https://poser.pugx.org/lrobert/gravatar/license.svg)](https://packagist.org/packages/lrobert/gravatar)

A library to make working with Gravatar in PHP easy.

## Requirements

lrobert\Gravatar requires the following:

- PHP 5.3+

## Installation
It is recommended that you install the lrobert\Gravatar library [through composer](http://getcomposer.org/). To do so, add
 the following lines to your ``composer.json``.
 
```json
{
    "require": {
        "lrobert/Gravatar": "dev-master"
    }
}
```

## Usages

The following is a basic example of the lrobert\Gravatar library.

```php
<?php

require_once('vendor/autoload.php');

$gravatar = new \lrobert\Gravatar\Gravatar();

?>

<img src="<?= $gravatar->getUrl('fake@example.com') ?>" alt="Example Avatar">

```

## Contributing

We welcome everyone to contribute to lrobert\Gravatar. Below are some of the things that you can do to contribute:

- Read [our contributing guide](https://github.com/lrobert/Gravatar/blob/master/CONTRIBUTING.md)
- [Fork us](https://github.com/lrobert/Gravatar/fork) and [request a pull](https://github.com/lrobert/Gravatar/pulls) to the [develop](https://github.com/lrobert/Gravatar/tree/develop) branch
- Submit [bug reports or feature requests](https://github.com/lrobert/Gravatar/issues) on GitHub
