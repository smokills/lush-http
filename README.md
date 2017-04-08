# Lush Http

[![Latest Version on Packagist](https://img.shields.io/packagist/v/appstract/lush-http.svg?style=flat-square)](https://packagist.org/packages/appstract/lush-http)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Build Status](https://img.shields.io/travis/appstract/lush-http/master.svg?style=flat-square)](https://travis-ci.org/appstract/lush-http)
[![Total Downloads](https://img.shields.io/packagist/dt/appstract/lush-http.svg?style=flat-square)](https://packagist.org/packages/appstract/lush-http)

##A Fast, Synchronous and Smart Http Client for PHP.

The goal is to delivery a small package for when you just need to make some Http calls, not to deliver a complex, expandable framework. 
We support the most common features you need when making Http calls.

[wip]

This package is still in development, you are free to try it, without any warranty.
When we release a final version, we will try to make it as backwards-compatible as possible and we will even try to support multiple versions in the same project, to avoid version conflicts.

Todo
- Support cookies
- More tests
- Docs


## Installation

You can install the package via composer:

``` bash
composer require appstract/lush-http
```

## Usage

``` php
    $api = new Lush('http://example.com');
    $response = $api->get('contacts', ['id' => 3]);
    
    // response returns json?
    // you can directly access it's properties
    echo $response->name;
```

## Testing

``` bash
$ composer test
```

## Contributing

Contributions are welcome, [thanks to y'all](https://github.com/appstract/lush-http/graphs/contributors) :)

## About Appstract

Appstract is a small team from The Netherlands. <3 Laravel, Vue and other awesome tools.

## Buy Us A Beer

Would be awesome if you would [buy us a beer](https://www.paypal.me/teamappstract/10)! Or [a lot of beer](https://www.patreon.com/appstract) :)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.