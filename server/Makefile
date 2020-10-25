up-postgres:
	docker run --name some-postgres -p 5432:5432 -e POSTGRES_USER=taxi -e POSTGRES_DB=taxi -e POSTGRES_PASSWORD=taxi -d postgres

up-redis:
	docker run --name some-redis -p 6379:6379 -d redis

up: up-postgres up-redis

env:
	export PGDATABASE=taxi
	export PGUSER=taxi
	export PGPASSWORD=taxi