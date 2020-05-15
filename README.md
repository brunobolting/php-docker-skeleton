# PHP Skeleton

This skeleton contains a Nginx web server, PHP 7.4, composer and PHPUnit.

## Composer
```sh
$ docker-compose run composer
```

## PHPUnit
```sh
$ docker-compose run phpunit
```

## WebServer
```sh
$ docker-compose up -d nginx
```
The webserver runs on `http://localhost:8080`

## Tip:
To simplify the commands, you can add a alias on your terminal, like this:
```sh
alias dcr='docker-compose run'
```
If you use this alias, you run `drc` instead `docker-compose run`

Example:
```sh
$ dcr phpunit
```

_Special thank's to https://thephp.website for the tutorial!_
