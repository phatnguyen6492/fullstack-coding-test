# [STARTER] Docker-NodeJS-MongoDB-React

Under the hood
--------
- NodeJS
- NestJs
- MongoDB
- Mongoose
- ReactJS
- Webpack
- Nginx (serving static content compiled by react)
- Docker
- docker-compose

## Prerequisites
- Docker
- docker-compose

Everything else will be pulled from Docker repositories !

Getting Started
---------------
Get source code
```
# clone repository, this main repo contains 2 submodule repo: 
# fullstack-coding-test-server for backend
# fullstack-coding-test-frontend for frontend
$ git clone https://github.com/phatnguyen6492/fullstack-coding-test.git
$ cd fullstack-coding-test
$ git submodule update --init --recursive
$ git submodule update --recursive --remote
```
Start applications
```
$ docker-compose up -d
```
Import data to mongo
```
#open second terminal and run seed (every time you execute it destroy DB and make new one)
$ docker-compose exec mongodb mongorestore -d nest /usr/src/mongodb/nest
```
Access React app via http://localhost:4000

Import POSTMAN link https://www.postman.com/collections/2f8fa652dfea3bc25dda

In case of problems*:* nnphat6492@gmail.com
