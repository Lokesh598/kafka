## Apache Kafka

Setting up kafka in windows...
first go to the directory where kafka-single-node.yml exists.
execute this command from current directory... [kafka-single-node](https://github.com/Lokesh598/kafka/blob/main/kafka-single-node.yml)

👉`docker-compose -f kafka-single-node.yml up -d
`

this command will pull the zookeeper and kafka. and start the containers of kafka and zookeeper.

![MicrosoftTeams-image (4)](https://user-images.githubusercontent.com/63910828/229498984-402c3d5f-7e96-48b0-b906-40a963846413.png)

To check the containers running or not ... execute this command

👉`docker ps`



To shutdown and remove the setup, execute this command in the same directory...

👉`docker-compose -f kafka-single-node.yml down`

Logging into kafka container...

👉`docker exec -it kafka-broker /bin/bash`

![MicrosoftTeams-image (5)](https://user-images.githubusercontent.com/63910828/229499073-6526f341-5286-4110-b9aa-019067682202.png)

Now navigate to kafka scripts directory...

👉`cd /opt/bitnami/kafka/bin`

