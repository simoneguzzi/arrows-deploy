# Arrows deploy

⚠️ Only use the secure HTTPs deployment for your production instance ⚠️

## Deploy without reverse proxy

```shell
docker compose -f docker-compose.yml up
```

## Deploy with test HTTP reverse proxy

```shell
docker compose -f docker-compose.yml -f services/traefik/test.yml up
```

## Deploy with production HTTPs reverse proxy

```shell
docker compose -f docker-compose.yml -f services/traefik/production.yml up
```
