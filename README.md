# docker_django
**step 1**

cd/mydjangoapp

**step 2**

docker build .

**wait**

**step 3**

docker-compose build

**step 4**

docker-compose up -d --build

**миграции**

**step 5**

docker-compose exec web python manage.py migrate --noinput