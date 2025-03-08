# E-commerce CDC Pipeline with Kafka & Debezium

This project sets up a multi-container environment using Docker Compose, integrating Kafka, Zookeeper, MongoDB, PostgreSQL, Debezium, and other services for real-time Change Data Capture (CDC).

## Prerequisites

Before running the project, ensure you have:
Docker installed on your system.
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
