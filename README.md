# 🤣 BobApp

Get a daily joke from this funny french Bob's App !

## 🛠 Software tools

- [Angular CLI](https://github.com/angular/angular-cli) 17
- [Java](https://www.oracle.com/java/technologies/downloads/) 11
- [Spring Boot](https://start.spring.io/;) 2
- [Docker](https://www.docker.com/products/docker-desktop/)

## 🛴 Start the project

Clone this repository :
> git clone https://github.com/duchenedaphne/bob-app

## Front-end 

Go inside the front folder:

> cd front

Install the dependencies:

> npm install

Launch Front-end:

> npm run start
or
> ng serve

### Docker

Build the container:

> docker build -t bobapp-front .  

Start the container:

> docker run -p 8080:8080 --name bobapp-front -d bobapp-front

## Back-end

Go inside the back folder:

> cd back

Install dependencies:

> mvn clean install

Launch Back-end:

>  mvn spring-boot:run

Launch the tests:

> mvn clean install

### Docker

Build the container:

> docker build -t bobapp-back .  

Start the container:

> docker run -p 8080:8080 --name bobapp-back -d bobapp-back 

## ✍ Workflow scripts author
Daphné Duchêne