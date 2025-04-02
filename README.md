# Laravel Project with Docker
This project contains the core setup needed to start a basic laravel installation with minimal setup. The project utilizes the LEMP stack (Linux, NGINX, MySQL, PHP) to setup a basic webserver.

## Prerequisites
Docker Desktop: https://www.docker.com/get-started/

## Getting Started
```
git clone git@github.com:bjwirgau/docker-laravel-project.git
docker compose run --rm composer create-project --prefer-dist laravel/laravel .
docker composer up -d server php mysql
```

Open your browser on http://localhost:8000 to verify laravel is running.