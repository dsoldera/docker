# RUNNING THIS APP INSIDE A DOCKER

## Creating the Image
- `docker build -t docker-api:v1 .`
- `docker image ls docker-api`
- `docker image history docker-api`

## Running the Image
- `docker run -p 3001:3000 -d docker-api:v1` 