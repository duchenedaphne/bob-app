# 🤣 BobApp

Get a daily joke from this funny french Bob's App !

## ✔ Code quality

<div>

[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=duchenedaphne_bobapp-back)](https://sonarcloud.io/summary/new_code?id=duchenedaphne_bobapp-back)
</div>

[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=duchenedaphne_bobapp-back&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=duchenedaphne_bob-app)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=duchenedaphne_bobapp-back&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=duchenedaphne_bob-app)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=duchenedaphne_bobapp-back&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=duchenedaphne_bobapp-back)

## 🛠 Software tools

- [Angular CLI](https://github.com/angular/angular-cli) 14
- [Java](https://www.oracle.com/java/technologies/downloads/) 11
- [Spring Boot](https://start.spring.io/;) 2
- [Docker](https://www.docker.com/products/docker-desktop/)

## 🛴 Start the project

Clone this repository :
> git clone https://github.com/duchenedaphne/bob-app

## Front-end 

1 - Go inside the front folder

> cd front

2 - Install the dependencies

> npm install

3 - Launch Front-end

> npm run start  

or  

> ng serve

### Docker

1 - Build the container

> docker build -t bobapp-front .  

2 - Start the container

> docker run -p 8080:8080 --name bobapp-front -d bobapp-front

## Back-end

1 - Go inside the back folder

> cd back

2 - Install dependencies

> mvn clean install

3 - Launch Back-end

>  mvn spring-boot:run

4 - Launch the tests

> mvn clean test

### Docker

1 - Build the container

> docker build -t bobapp-back .  

2 - Start the container

> docker run -p 8080:8080 --name bobapp-back -d bobapp-back 

## ✍ Workflow scripts author
Daphné Duchêne