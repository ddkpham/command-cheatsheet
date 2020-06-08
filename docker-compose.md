### Docker compose 

#### For clean up:

1. Stops any running containers by docker compose, cleans them up, and removes all associated resources. 

`docker-compose down`

2. Removes saved volume bindings 

`docker system prune --volumes`

Here are a few basic commands to get started working with docker-compose:
Build any images from Dockerfiles described in your docker-compose.yml.

`docker-compose build`

Start all of the containers described in your docker-compose.yml. Press control-C to stop them.

`docker-compose up`

Stop and remove all of the containers described in your docker-compose.yml.

`docker-compose down`

Remove any unused containers and images.

`docker system prune`
As above, but also remove any volumes.

`docker system prune --volumes`

Run a command (bash) in a new instance of the container (app).
`docker-compose run app bash`

Run a command (bash) in an existing container (exercise4_web_1).
`docker exec -it exercise4_web_1 bash`
