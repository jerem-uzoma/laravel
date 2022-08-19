<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>
<p align="center">Empty Laravel Project with ide-helper Plugin</p>

## Usage

Clone project and execute following tasks:

```
composer update
mv .env.example .env
php artisan key:generate
```

To dockerize run the command:

docker build -f .docker/Dockerfile -t test .

To build the pipeline:

Add a gitlab runner to your env and assign an instance role to this runner with ecr access.


