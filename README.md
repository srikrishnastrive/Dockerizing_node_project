# Dockerization of Node.js Module

This repository contains a Node.js module that has been Dockerized to run in a Docker container.

## Prerequisites

- Docker
- Node.js

## Setup Instructions

### 1. Clone the Repository
git clone https://github.com/your-username/node-module.git
cd node-module

### 2.run this project
docker build -t node-module-image .

### 3.To create the container
docker run -p 8080:8080 --name node-module-container node-module-image

### 4.Acess the application
http://localhost:8080

## Additional Commands
### Stop Container

docker stop node-module-container
### Remove Container
docker rm node-module-container
### Remove Image

docker rmi node-module-image