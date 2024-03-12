# About project

- Here you can find custom Docker Image files, and docker compose files to dockerize different apps

# Instructions

`/node` folder include
- Dockerfile to build node app
- docker-compose to build node app with postgreSQL DB

To start the app

- Populate variables in .env
- create `start` script to package.json
- Run `docker compose up`

`/wordpress/mysql` folder include
- docker-compose to build wordpress app with mySQL DB and adminer

To start the wp app

- Populate variables in .env
- Run `docker compose up`

