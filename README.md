# Steps
* Get last version of Docker
* Pull `docker.elastic.co/logstash/logstash:5.3.0`
* Pull `docker.elastic.co/kibana/kibana:5.3.0`
* Pull `docker.elastic.co/elasticsearch/elasticsearch:5.3.0`
* Run `docker-compose up`


# Notes

* Remove all indexes: `curl -XDELETE http://localhost:9200/_all`
