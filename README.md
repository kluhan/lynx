# Lynx - Docker Compose Collection
A collection of Docker Compose files for various applications and services intended for local development. 

## Usage
First of all, this repository is intended for local development and testing purposes only. It is not recommended to use these configurations in production environments. 

To use any of the Docker Compose files, simply clone this repository and navigate to the desired directory. Then run:

```bash
docker-compose up
```

## Available Services
- **Traefik**: A modern reverse proxy and load balancer, used to route traffic to various services.
- **Portainer**: A lightweight management UI for Docker, allowing you to easily manage your containers, images, networks, and volumes.
- **MongoDB**: A NoSQL database, used for storing data in a flexible, JSON-like format.
- **MinIO**: An object storage service, compatible with Amazon S3 APIs, used for storing large amounts of unstructured data.
- **Aim**: An open-source tool for tracking machine learning experiments, providing a user interface to visualize and compare results.

