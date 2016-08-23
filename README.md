## Elasticsearch-2.3.5, Kibana-4.5.3, Marvel and Sense in one container

Simple and lightweight docker image for previewing Elasticsearch, Kibana, Marvel and Sense.

### Usage

    docker run -d -p 9200:9200 -p 5601:5601 arcseldon/elasticsearch-kibana-marvel-sense

You can connect to Elasticsearch with `http://localhost:9200` and its Kibana front-end with `http://localhost:5601`.

You can connect to Marvel with `http://localhost:5601/app/marvel` and Sense with `http://localhost:5601/app/sense`
 

### Tags

* latest

    Elasticsearch Kibana Marvel Sense

### Tips

* To install plugins just view the Dockerfile and copy a line similar to your needs and modify as needed 


