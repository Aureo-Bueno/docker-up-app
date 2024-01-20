# Docker Compose for Database Services

This repository contains a Docker Compose file for running MySQL, PostgreSQL, SQL Server, and MongoDB containers.

## Prerequisites

- Docker
- Docker Compose

## Getting Started

1. Clone this repository:

```bash
git clone <>
```

## Start and Stop 

```bash
docker-compose up -d
```

```bash
docker-compose down
```

## Accessing Container Logs

You can access the logs of the containers running with Docker Compose using the `docker-compose logs` command.

To view the logs for all the containers, you can use the following command:

```bash
docker-compose logs
```

```bash
docker-compose logs -f
```

```bash
docker-compose logs postgres
```

```bash
docker-compose logs sqlserver
```

```bash
docker-compose logs mongo
```

```bash
docker-compose logs mysql
```
