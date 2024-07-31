# redis-docker-deployment
This is a redis docker-deployment repository which is having sufficient files to deploy a redis image as a docker container. The files given in this repository will have the capability to run a redis service as a docker container with a username and password.

# Redis
Redis is a source-available, in-memory storage, used as a distributed, in-memory key–value database, cache and message broker, with optional durability.

# Docker Image
[Redis Docker hub page](https://hub.docker.com/_/redis)

# How to run
1. Change the username and password in the `users.acl` file if needed.
2. Run the docker-compose.yaml using the command `docker compose up -d`.

# How to use redis cli
1. Exec into the redis docker container using the command `docker exec -it redis-server sh`.
2. Enter into the redis cli using the command `redis-cli`.
3. authorize the user using `AUTH redisuser redispass`.
