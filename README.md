# ecommerce-project

This project uses Docker Compose to set up a multi-container environment with Kafka, Zookeeper, MongoDB, PostgreSQL, and other services. The following instructions will guide you on how to run and stop the containers.

## Prerequisites

- Docker: [Install Docker](https://docs.docker.com/get-docker/)

## Running the Docker Containers

To start all the services defined in the `docker-compose.yml` file, run the following command:

```bash
docker-compose up --build -d
```
Once the containers are running, you can inspect them using:

```bash
docker ps
```

## Access the following services locally:
    - pgAdmin: http://localhost:5050
    - Control Center: http://localhost:9021
