# Docker Strapi Postgres

A simple docker compose configuration to get up and running quickly with Strapi locally

## Requirements

- Docker `v20.10.11`

## Local Setup

**NOTE:** You might need to wait for Strapi to install all its dependencies

```bash
docker compose up -d;
# docker compose up;
```

To delete the docker container:

```bash
docker compose down --remove-orphans -v;
```