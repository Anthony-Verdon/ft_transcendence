# Ft_transcendence

## Make a pong game, but with some extras

This project is the last one of the 42 common core. The goal is to create a single page application, with some features. For that, I was with my friend Théo Guerin (login 42 : tguerin, Github account : https://github.com/TheoGuerin64) and Unai Layus (login 42 : ulayus, Github account : https://github.com/0x35c). You will find the subject of the project into the repository. My grade : 100/100

## What did we used

In the subject, we must have a framework of your choice for the front, NestJS for the back and a PostgreSQL database. For the front, we chose VueJS. We also used ThreeJS which is a 3D Library for the game, and Bulma which is a CSS Library. Finally, we had a container for PGAdmin to see the database. 

## How to use it 

1. Install Docker `https://docs.docker.com`
2. Install Docker Compose `https://docs.docker.com/compose/install/`
3. Clone it `git clone git@github.com:AnthonyVerdon-42Projects/ft_transcendence.git`.
4. run `make`

## What can you do

- connect using 42 API
- edit your profile
- interact with people
- play a pong game against them

For more details, you will find the subject of the project into the repository.

## My part

Personally, I implemented the game and handle the user statistics.
For more details, you will find the subject of the project into the repository.

## .env

* Required variables:
  * [INTRA42_UID](https://profile.intra.42.fr/oauth/applications)
  * [INTRA42_SECRET](https://profile.intra.42.fr/oauth/applications)
  * [INTRA42_REDIRECT_URI](https://profile.intra.42.fr/oauth/applications)
  * [POSTGRES_USER](https://github.com/docker-library/docs/blob/master/postgres/README.md#postgres_user)
  * [POSTGRES_PASSWORD](https://github.com/docker-library/docs/blob/master/postgres/README.md#postgres_password)
  * [PGADMIN_DEFAULT_EMAIL](https://www.pgadmin.org/docs/pgadmin4/latest/container_deployment.html)
  * [PGADMIN_DEFAULT_PASSWORD](https://www.pgadmin.org/docs/pgadmin4/latest/container_deployment.html)
  * JWT_SECRET (minimum 50 char)
  * TWOFA_PASSWORD
  * [TWOFA_SALT](https://en.wikipedia.org/wiki/Salt)

## Find a bug ?

If you find an undefined behaviour (crash, leaks, ...), please submit an issue or contact me