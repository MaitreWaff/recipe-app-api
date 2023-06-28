# recipe-app-api
Recipe API Project.


# Building the image

# docker-compose build


# Migrating the image DataBase

# docker-compose run --rm app sh -c "python manage.py makemigrations"


# Testing the image

# docker-compose run --rm app sh -c "python manage.py test && flake8"


# Running the application

# docker-compose run --rm app sh -c "python manage.py test && flake8"
