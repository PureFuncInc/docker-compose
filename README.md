# docker-compose
> $_purefunc service collections with docker-compose

# List
* Redis
* RabbitMQ
* PostgreSQL
* MySQL
* MongoDB
* Elastic Stack
  * Kibana
  * Elastic
    * dco -f docker-compose-arm.yaml logs -f kibana 
    * dco -f docker-compose-arm.yaml exec elasticsearch /usr/share/elasticsearch/bin/elasticsearch-create-enrollment-token -s kibana 
    * dco -f docker-compose-arm.yaml exec elasticsearch /usr/share/elasticsearch/bin/elasticsearch-reset-password -u elastic
    * dco -f docker-compose-arm.yaml cp elasticsearch:/usr/share/elasticsearch/config/certs/http_ca.crt .
    * curl --cacert http_ca.crt -u elastic:lOO-446FcLp=HJnbAs+5 https://localhost:9200
* Grafana Stack
  * Grafana
  * Loki
  * Prometheus
