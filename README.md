# Webapp Docker

Docker images for CodeOcean Webapp

## Deploy

```bash
git clone this repository
cd codeocean-docker
docker build
```
## Configure it

```bash
docker-compose run codeocean-source
docker-compose run --rm php artisan key:generate
```

## Run it

```bash
docker-compose up -d
```
