# mongo-cluster-docker

Simple 3 node mongo replica set using `docker-compose`.

Relies on a docker network called `my-mongo-cluster` which can be created via the following command:
```
docker network create my-mongo-cluster
```


# Run

```
docker-compose up
```
