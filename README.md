# Simple LEPP Docker Containers

This is docker containers composed as simple LEPP server, which as nginx, php-fpm, workpsace, postgres-postgis, redis,
pgadmin, redis-webui, mailhog

## Base CLI Commands

    docker compose build

    docker compose ud -d

    docker compose exec -u laradock workspace bash

    docker compose exec postgres-postgis psql -U default

    docker compose exec nginx nginx -t

    docker compose exec nginx nginx -s reload

