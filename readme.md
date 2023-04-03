## Apache Kafka

Setting up kafka in windows...
first go to the directory where kafka-single-node.yml exists.
execute this command from current directory... `https://github.com/Lokesh598/kafka/blob/main/kafka-single-node.yml`

👉`docker-compose -f kafka-single-node.yml up -d
`

this command will pull the zookeeper and kafka. and start the containers of kafka and zookeeper.

To check the containers running or not ... execute this command

👉`docker ps`

![MicrosoftTeams-image (4).png](..%2F..%2F..%2FMicrosoftTeams-image%20%284%29.png)

To shutdown and remove the setup, execute this command in the same directory...

👉`docker-compose -f kafka-single-node.yml down`

Logging into kafka container...

👉`docker exec -it kafka-broker /bin/bash`

![MicrosoftTeams-image (5).png](..%2F..%2F..%2FMicrosoftTeams-image%20%285%29.png)

Now navigate to kafka scripts directory...

👉`cd /opt/bitnami/kafka/bin`

