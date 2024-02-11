´´´
docker network list

docker network create laranet

// to run

docker run-d --network laranet --name laravel laravel:prod
docker run-d --network laranet --name nginx -p 8080:80 nginx:prod
