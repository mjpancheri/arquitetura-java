# Java Architecture Project

This is a sample Java project that demonstrates a microservices architecture using Docker Compose. It consists of a MySQL database and a Java application that depends on the database.

## Prerequisites

- Docker
- Docker Compose
- MySQL

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/your-username/java-architecture-project.git
cd java-architecture-project
```

2. Create a .env file in the env directory with the following environment variables:

## MySQL environment variables
MYSQL_ROOT_PASSWORD=your-root-password
MYSQL_USER=your-username
MYSQL_PASSWORD=your-password
MYSQL_DATABASE=your-database-name

## Java application environment variables
SPRING_DATASOURCE_URL=jdbc:mysql://mysql:3306/your-database-name
SPRING_DATASOURCE_USERNAME=your-username
SPRING_DATASOURCE_PASSWORD=your-password


3. Build and start the containers:

```bash
docker-compose up -d --build
```
This will build the Java application image and start the MySQL and Java application containers.

4. Access the application at http://localhost:8080


This README provides an overview of the project, prerequisites, instructions for getting started, project structure, contributing guidelines, and licensing information. Feel free to modify it as needed to better suit your project.
