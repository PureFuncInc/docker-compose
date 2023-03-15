# docker-compose
> $_purefunc service collections with docker-compose

# List
* Redis
  * docker-compose -f docker-compose-x86.yaml up -d redis
  * docker-compose -f docker-compose-x86.yaml up -d redis-exporter
* RabbitMQ
  * docker-compose -f docker-compose-x86.yaml up -d rabbitmq
* PostgreSQL
  * docker-compose -f docker-compose-x86.yaml up -d posgresql
  * docker-compose -f docker-compose-x86.yaml up -d posgresql-exporter
* MySQL
  * docker-compose -f docker-compose-x86.yaml up -d mysql
  * docker-compose -f docker-compose-x86.yaml up -d mysql-exporter
* MongoDB
  * docker-compose -f docker-compose-x86.yaml up -d mongodb
* Grafana Stack
  * docker-compose -f docker-compose-x86.yaml up -d grafana
  * docker-compose -f docker-compose-x86.yaml up -d loki
  * docker-compose -f docker-compose-x86.yaml up -d prometheus
  
# TODO:
* Elastic Stack
