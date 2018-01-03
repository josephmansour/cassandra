# Cassandra
Un Didacticiel concernant Cassandra 3.11 

create table chambres (


docker run --name cassandra-node1 -d -m="1500m"  cassandra:3.11.1 
docker run --name cassandra-node2 -d -m="1500m" -e CASSANDRA_SEEDS="$(docker inspect --format='{{ .NetworkSettings.IPAddress }}' cassandra-node1)" cassandra:3.11.1
docker run --name cassandra-node3 -d -m="1500m" -e CASSANDRA_SEEDS="$(docker inspect --format='{{ .NetworkSettings.IPAddress }}' cassandra-node1)" cassandra:3.11.1
docker run --name cassandra-client -d -m="500m" cassandra:3.11.1
create keyspace demo_kspc WITH REPLICATION = { 'class' : 'SimpleStrategy', 'replication_factor' : 2 };
use demo_kspc
