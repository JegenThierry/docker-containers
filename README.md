# Docker Containers

A collection of ready-to-use Docker configurations for various services and applications. This repository has some personal containers and tools that can be run using `docker-compose`.

## The Collection

| Container | Description |
| ----------- | ----------- |
| Basic Webserver 🌐 | A basic webserver for hosting static content. |
| Nextcloud ☁️ | A Nextcloud docker-aio adaptation for personal use. |
| Postgres 🐘 | DB-System. |

## Getting Started

Each directory in this repository includes a `docker-compose.yml` file, pre-configured for rapid deployment.

### Deploying a Container
Navigate to the directory of the service you wish to start:

```bash
cd nextcloud
```

Adsjust all passwords and username

```bash
docker-compose up -d
```
