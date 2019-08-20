# Slim 4 Skeleton for Apache

This is a simple web application skeleton project that uses the [Slim 4 Framework](https://www.slimframework.com/):

- [nyholm/psr7](https://github.com/nyholm/psr7) as super lightweight PSR-7 implementation
- [sebastianbergmann/phpunit](https://github.com/sebastianbergmann/phpunit) as Unit Testing framework

## Requirements

* PHP 7.2+
* Composer

## Installation

* Download and extract the ZIP file: [master.zip](https://github.com/odan/slim4-hello-world/archive/master.zip)
* Run: `composer update`
* Upload all files to the webserver
* Open the website
* You should see a message: `Hello, World!`

## Routes

* `/` => `Hello, World!`
* `/hello/john` => `Hello, john!`

## Tests

Start API integration tests with:

```
composer test
```

Start API integration tests with full coverage report:

```
composer test-coverage
```
