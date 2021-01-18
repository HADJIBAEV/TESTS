# Задание 3. Профиль на hub.docker.com и ссылка на решение задания с sqlite + flask

## Author
Kahramon Hadjibaev

## Stack
Python, SQLite, Docker

## Installation and usage of the project
**Please make sure that you have docker and docker-compose installed on your PC (Notebook)**

1\) Pull images on disk::

```
docker pull khadjibaev/flaskapp:latest
```

2\) Run containers from the root of the project::

```
Docker run --name flaskappdemo -d -p 5000:5000 khadjibaev/flaskapp
```

3\) Visit http://localhost:5000/ and http://localhost:5000/plus to start using the app

**SQLite database is persistent** since data located in volume.

