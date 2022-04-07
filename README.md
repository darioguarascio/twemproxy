# twemproxy

Very basic twemproxy image for docker.

## Setup

Create a config file, then edit `docker-compose.yml`:
```
    volumes:
      - ./your-config-file.yml:/etc/twemproxy.yml
```

## Startup

`docker-compose up --build`
