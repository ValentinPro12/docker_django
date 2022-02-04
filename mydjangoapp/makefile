CC := docker-compose
build_run: build run

makemigrations_migrate: makemigrationsmigrate



build:
	$(CC) build

run:
	$(CC) up -d

makemigrations:
	$(CC) exec web python manage.py makemigrations

migrate:
	$(CC) exec web python manage.py migrate --noinput

stop:
	$(CC) stop

clean:
	$(CC) down --rmi all

createsuperuser:
	$(CC) exec web python manage.py createsuperuser