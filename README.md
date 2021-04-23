# ams-environment
 Environment for Software Engineering Project SP21

### Installation

Running the commands below will allow you to spin up the CARDS system. 

```sh
$ cd ams-environment
$ git submodule init
$ git submodule update
$ docker-compose -f overrides/docker-compose.mongo.yml up
```
Open a new tab 
```sh
$ cd appointment-service
$ npm install
$ npm start
```
Open a new tab 
```sh
$ cd clinic-client
$ npm install
$ ng serve
```
### Ports 

MongoDB: http://localhost:27017 

MongoDB Dashboard: http://localhost:8081

appointment-service: http://localhost:3000

clinic-client: http://localhost:4200
