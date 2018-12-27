# Dockerized Slanger

[![](https://images.microbadger.com/badges/image/stankec/slanger.svg)](https://microbadger.com/images/stankec/slanger
"Get your own image badge on microbadger.com")

Docker image for
[Steve Graham's Slanger](https://github.com/stevegraham/slanger).

## About

This project aims to create an image that makes no assumptions about your
configuration.

## Instalation

Add the image to your machine by running the following command:

```BASH
docker pull stankec/slanger
```

Alternatively, visit [docker.com](https://hub.docker.com/r/stankec/slanger/)
for more ingormation about this project.

## Configuration

The `app_key`, `secret` and `redis_address` can be set throught the `APP_KEY`,
`SECRET` and `REDIS_URL` environment variables.
