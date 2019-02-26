# PHP_CodeSniffer Docker image

## Supported tags

* latest

## What is PHP_CodeSniffer?

PHP_CodeSniffer is a script that tokenizes PHP, JavaScript and CSS files to detect violations of a defined coding standard.

> https://github.com/squizlabs/PHP_CodeSniffer

## How to use this image

```console
docker run --volume </local/path>:/project hlacos/phpcs[:tag] [<options>]
```

Example:
```console
docker run --volume /project/path:/project hlacos/phpcs phpcs --standard=PSR1,PSR2 /project
```
