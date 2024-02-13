´´´
docker-compose up -d --build

docker exec -it docker_app_1 bash
docker exec -it db bash

mysql -uroot -p
create table people(id int not null auto_increment, name varchar(255), primary key(id));

´´´
