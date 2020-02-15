# Grafana docker

This is a study of docker environment for starting grafana.

STATEMENT: the Dockerfile is intially a copy of original grafana's Dockerfile. This is by adding docker-compose and manage the environment viriables using .env file.

## Installation

```
$ git clone https://github.com/BalaWxd/grafana-docker.git
$ cd grafana-docker
$ cp env-example .env

# Change mynamesapce to whatever you want!
$ docker-compose -p mynamespace up -d

# Check if the container starts
$ docker-compose -p mynamespace ls 
```

Open browser: http://localhost:3000
