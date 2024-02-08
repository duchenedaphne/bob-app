# 🤣 BobApp

Get a daily joke from this funny french Bob's App !

<p>
    <a href="https://github.com/duchenedaphne/bob-app/actions/workflows/front-build-test.yml">
        <img src="https://github.com/duchenedaphne/bob-app/actions/workflows/front-build-test.yml/badge.svg" alt="Front Build & Test" style="max-width: 100%;">
    </a>
    <a href="https://github.com/duchenedaphne/bob-app/actions/workflows/back-build-test.yml">
        <img src="https://github.com/duchenedaphne/bob-app/actions/workflows/back-build-test.yml/badge.svg" alt="Back Build & Test" style="max-width: 100%;">
    </a>
</p>
<p>
    <img src="https://img.shields.io/github/languages/code-size/duchenedaphne/bob-app" alt="GitHub code size in bytes">
    <img src="https://img.shields.io/github/commit-activity/w/duchenedaphne/bob-app" alt="GitHub commit activity">
    <a href="https://github.com/duchenedaphne/bob-app/issues">
        <img src="https://img.shields.io/github/issues/duchenedaphne/bob-app" alt="GitHub issues">
    </a>
</p>

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