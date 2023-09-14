# Database Stack

Compose stack, with needed databases for database classes.

## Description

The project deploys five databases (MSSQL, MySQL, PostgreSQL, MongoDB, and Adminer) alongside a MongoDB web interface called mongo-express. It maps the respective ports for each service to the host and sets root or admin access credentials. Additionally, it ensures that services automatically restart unless they are explicitly stopped.

## Getting started

### Dependencies

* [Docker Desktop](https://www.docker.com/products/docker-desktop/) or similar docker solution
* Docker compose (is included in Docker Desktop)
* A terminal interface, e.g. Powershell, Bash, Zsh etc.

### Running the stack

Navigate to the project folder in your CLI tool, and run the following command:

```sh
docker compose -f ./database-compose.yml up -d
```

### Stopping the stack

```sh
docker compose -f ./database-compose.yml down
```
