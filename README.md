# AZinkey's Slim-Skeleton
A Micro App skeleton with some essential packages for rapid development

Start by creating the composer.json file:
```
{
    "name": "azinkey/slim-skeleton",
    "description": "A Micro App skeleton with some essential packages for rapid development",
    "keywords": ["microframework", "rest", "router", "psr7","slim","azinkey"],
    "homepage": "https://github.com/azinkey/slim-skeleton",
    "license": "N/A",
    "authors": [
        {
            "name": "AZinkey",
            "email": "azinkey@gmail.com",
            "homepage": "google 'azinkey' "
        }
    ],
    "require": {
        "php": ">=5.5.0",
        "slim/slim": "^3.1",
        "slim/csrf": "^0.8.3",
        "slim/flash": "^0.4.0",
        "slim/php-view": "^2.0",
        "slim/twig-view": "^2.5",
        "vlucas/valitron": "^1.4",
        "monolog/monolog": "^1.17",
        "illuminate/database": "^5.8",
        "dopesong/slim-whoops": "^2.3",
        "illuminate/pagination": "^5.8",
        "illuminate/filesystem": "^5.8",
        "bryanjhv/slim-session": "^3.6",
        "tuupola/slim-jwt-auth": "^3.3",
        "itsgoingd/slim-facades": "^1.0",
        "andrewdyer/slim3-mailer": "^1.1",
        "davidepastore/slim-config": "^0.1.1",
        "martynbiz/slim3-controller": "^0.0.0"
    },
    "require-dev": {
        "phpunit/phpunit": ">=4.8 < 6.0"
    },
    "autoload-dev": {
        "psr-4": {
            "Tests\\": "tests/"
        }
    },
    "config": {
        "process-timeout" : 0
    },
    "scripts": {
        "start": "php -S localhost:8080 -t public",
        "test": "phpunit"
    }

}
```

```sh
$ composer install
```

### Packages

Need to say Thanks.

| Plugin | README |
| ------ | ------ |
| slim | [http://www.slimframework.com/docs] |
| csrf | [] |
| flash | [] |
| php-view | [] |
| twig-view | [] |
| monolog | [] |
| valitron | [] |
| slim-session | [] |
| slim-config | [] |
| slim-facades | [] |
| slim3-mailer | [] |
| slim-jwt-auth | [] |
| i/database | [] |
| i/pagination | [] |
| i/filesystem | [] |


