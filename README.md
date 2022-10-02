# market-app
Super Market API Django Project.

docker-compose build  // builds the image.
docker-compose down  // removes the containers
docker-compose run --rm app sh -c "flake8"  // Check the app with flake8 linting tool.
docker-compose up  // first up the services.
docker-compose run --rm app sh -c "django-admin startproject app ." // create a new project.
docker-compose run --rm app sh -c "python manage.py test" // testing
docker-compose run --rm app sh -c "python manage.py makemigrations" // migrations
docker-compose run --rm app sh -c "python manage.py migrate" //migrate the migrations
 docker-compose run --rm app sh -c "python manage.py createsuperuser" // create superuser