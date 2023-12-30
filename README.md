# Prometheus docker-compose file

## Basic auth
https://prometheus.io/docs/guides/basic-auth/

### Laucn docker-compose

#### Local
```
docker-compose -f docker-compose.yml --env-file=.local.env up -d
```

#### Production
```
docker-compose -f docker-compose.yml --env-file=.prod.env up -d
```
