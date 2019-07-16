# Practice MREN + Docker + AWS
Create Mongo-Express-React-Node (MERN) app with Docker and deploy it to AWS

## Reference
- How to create a full stack React/Express/MongoDB app using Docker
  - https://github.com/Joao-Henrique/Docker_Medium_Tutorial
  - https://github.com/gonzalompp/todolist-reactjs-example

- A Complete Guide To Deploying Your Web App To Amazon Web Service

- MERN EP01: Setting up a development environment with Docker

- 

## Notes


## Docker-compose
You could run each individual container using the Dokerfiles. In our case we have 3 containers to manage, so we will use docker-compose instead. Compose is a tool for defining and running multi-container Docker applications.

Build images
```
docker-compose build
```

Run the dockers
```
docker-compose up
```