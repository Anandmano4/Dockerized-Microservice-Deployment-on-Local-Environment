# Dockerized Microservice Deployment on Local Environment

## Overview

This project demonstrates how to containerize a simple Flask-based microservice using Docker and Docker Compose. The microservice provides a basic API that returns a JSON response when accessed. The setup is designed to run locally using Docker containers.

## Prerequisites

- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/)

Verify the installation by running the following commands in your terminal:

```bash
docker --version
docker-compose --version

# Clone the repository to your local machine
git clone https://github.com/yourusername/microservice-docker.git
cd microservice-docker

# Build the Docker Image
docker-compose build
# Run the Microservice
docker-compose up

# Access the Microservice
http://localhost:5000/

You should see the following response:

{"message": "Hello, Dockerized Microservice!"}

# Stop the service 
docker-compose down
