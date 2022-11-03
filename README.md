# React template

## Technologies

- [X] React
- [X] Docker

## Environments

This template is thought and designed for the docker environment. It is not recommended to use it without docker.


### How to use Docker dev

1. run `docker-compose -f docker-compose-local-dev.yml up --build` for local dev or `docker-compose -f docker-compose-prod.yml up --build` for prod
2. work with your local files
3. execute commands inside the container. ex `docker exec -it django_template-app_1 python manage.py makemigrations`