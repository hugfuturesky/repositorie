docker run --name my-redis -p 6379:6379 -d redis

docker exec -it my-redis redis-cli -h 127.0.0.1 -p 6379
docker exec -it my-redis redis-cli -h 172.17.0.3 -p 6379

//TODO