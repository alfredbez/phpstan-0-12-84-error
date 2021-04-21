```
composer install
docker run -it --rm -v $(pwd):/app -w /app spryker/php:7.3 vendor/bin/phpstan
```
