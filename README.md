# dockerized-flask-app

A dead simple dockerized hello world flask app.

# Setup

## Install docker

This project requires docker to run.

-   Windows: https://docs.docker.com/docker-for-windows/install/
-   Mac: https://docs.docker.com/docker-for-mac/install/

# Build the docker image

You can build the docker image 1 of two ways:

## Docker CLI

```bash
docker build -t dockerized-flask-app:latest .
```

## Docker Compose

```bash
docker-compose build
```

# Run the app

The prefered method of running this app is with docker-compose.

```bash
docker-compose up
```

Stopping the app is now as easy as:

```bash
docker-compose down
```

You can also run the container with docker as a daemon, if you want:

```bash
docker run -p 5000:5000 dockerized-flask-app
```
