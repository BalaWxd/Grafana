# Grafana docker

This is a study of docker environment for starting grafana.

STATEMENT: the Dockerfile is intially a copy of original grafana's Dockerfile. This is by adding docker-compose and manage the environment viriables using .env file.

## Installation

```
$ git clone https://github.com/BalaWxd/grafana-docker.git
$ cd grafana-docker
$ cp env-example .env
$ docker-compose -p mynamespace up -d
```
