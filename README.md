# RIPIO API
Ripio API source code

### MAKE MIGRATIONS
`docker-compose run --rm app sh -c "python manage.py makemigrations core"`

### RUN TESTS
`docker-compose run --rm app sh -c "python manage.py test && flake8"`

### RUN APPLICATION
`docker-compose up`