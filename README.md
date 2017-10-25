# docker-caddy


A Docker container for the Caddy web server (https://github.com/mholt/caddy)


# Status

[![Docker Pulls](https://img.shields.io/docker/pulls/bodsch/docker-caddy.svg?branch)][hub]
[![Image Size](https://images.microbadger.com/badges/image/bodsch/docker-caddy.svg?branch)][microbadger]
[![Build Status](https://travis-ci.org/bodsch/docker-caddy.svg?branch)][travis]

[hub]: https://hub.docker.com/r/bodsch/docker-caddy/
[microbadger]: https://microbadger.com/images/bodsch/docker-caddy
[travis]: https://travis-ci.org/bodsch/docker-caddy


# Build

Your can use the included Makefile.

To build the Container: `make build`

Starts the Container: `make run`

Starts the Container with Login Shell: `make shell`

Entering the Container: `make exec`

Stop (but **not kill**): `make stop`

History `make history`


# Usage

Look at the `Makefile` for Examples. :)


# Docker Hub

You can find the Container also at  [DockerHub](https://hub.docker.com/r/bodsch/docker-caddy)

## get

    docker pull bodsch/docker-caddy


# Ports

  - 80
  - 443
  - 2015
