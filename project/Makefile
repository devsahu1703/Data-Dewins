default: up

prepare: pscript.sh
	bash pscript.sh

up:
	docker-compose up

down:
	docker-compose down

teardown:
	docker-compose down
	sudo rm -rf ./docker/*
