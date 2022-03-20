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
```
# clone repository
$ git clone https://github.com/phatnguyen6492/fullstack-coding-test.git
$ cd fullstack-coding-test
```
First run
```
$ docker-compose up -d

#open second terminal and run seed (every time you execute it destroy DB and make new one)
$ docker-compose exec mongodb mongorestore -d nest /usr/src/mongodb/nest
```

Access React app via http://localhost:4000

In case of problems: nnphat6492@gmail.com
