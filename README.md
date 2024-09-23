# Microservice Architecture

This repository demonstrates a microservice architecture using Spring Boot. It includes the following services:

- **Product Service**
- **Order Service**
- **Inventory Service**

## Features

- **Inter-Service Communication**: Utilizes OpenFeign for service-to-service communication.
- **Dockerized**: Services run in Docker containers via Docker Compose.
- **Ports**:
  - Product Service: `8080`
  - Order Service: `8081`
  - Inventory Service: `8082`

## Prerequisites

- Docker
- Maven

## Running the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/merveozer/microservice.git
2. Navigate to the project directory:
   ```bash
   cd microservice
3. Build and run the services using Docker Compose:
    ```bash
    docker-compose up --build

## Endpoints
## Product Service: http://localhost:8080
## Order Service: http://localhost:8081
## Inventory Service: http://localhost:8082
