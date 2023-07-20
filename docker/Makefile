include ./.env

app:
	docker-compose exec app bash
build:
	docker-compose stop
	docker-compose up -d --build
init:
	docker-comopose exec app /bin/bash -c "cd website-skeleton && composer install"
restart:
	docker-compose stop
	docker-compose up -d
stop:
	docker-compose stop
up:
	docker-compose up -d
web:
	docker-compose exec web /bin/sh
