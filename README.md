This Docker image is based on the sebp/elk docker image. 

run:

docker run -p 5601:5601 -p 9200:9200 -p 4560:4560 -it --name elk zhaohuabing/elk-docker

Modification:
- Add Logstash TCP input config, the listening port is 4560, so it can work with  [The Logstash Logback Appender](https://github.com/logstash/logstash-logback-encoder).

Below is the original information of sebp/elk docker image:

# Elasticsearch, Logstash, Kibana (ELK) Docker image

[![](https://badge.imagelayers.io/sebp/elk:latest.svg)](https://imagelayers.io/?images=sebp/elk:latest 'Get your own badge on imagelayers.io')

This Docker image provides a convenient centralised log server and log management web interface, by packaging Elasticsearch, Logstash, and Kibana, collectively known as ELK.

The following tags are available:

- `latest`, `520`: Elasticsearch 5.2.0, Logstash 5.2.0, and Kibana 5.2.0.

- `512`: Elasticsearch 5.1.2, Logstash 5.1.2, and Kibana 5.1.2.

- `511`: Elasticsearch 5.1.1, Logstash 5.1.1, and Kibana 5.1.1.

- `502`: Elasticsearch 5.0.2, Logstash 5.0.2, and Kibana 5.0.2.

- `es501_l501_k501`: Elasticsearch 5.0.1, Logstash 5.0.1, and Kibana 5.0.1.

- `es500_l500_k500`: Elasticsearch 5.0.0, Logstash 5.0.0, and Kibana 5.0.0.

- `es241_l240_k461`: Elasticsearch 2.4.1, Logstash 2.4.0, and Kibana 4.6.1.

- `es240_l240_k460`: Elasticsearch 2.4.0, Logstash 2.4.0, and Kibana 4.6.0.

- `es235_l234_k454`: Elasticsearch 2.3.5, Logstash 2.3.4, and Kibana 4.5.4.

- `es234_l234_k453`: Elasticsearch 2.3.4, Logstash 2.3.4, and Kibana 4.5.3.

- `es234_l234_k452`: Elasticsearch 2.3.4, Logstash 2.3.4, and Kibana 4.5.2.

- `es233_l232_k451`: Elasticsearch 2.3.3, Logstash 2.3.2, and Kibana 4.5.1.

- `es232_l232_k450`: Elasticsearch 2.3.2, Logstash 2.3.2, and Kibana 4.5.0.

- `es231_l231_k450`: Elasticsearch 2.3.1, Logstash 2.3.1, and Kibana 4.5.0.
 
- `es230_l230_k450`: Elasticsearch 2.3.0, Logstash 2.3.0, and Kibana 4.5.0.

- `es221_l222_k442`: Elasticsearch 2.2.1, Logstash 2.2.2, and Kibana 4.4.2.

- `es220_l222_k441`: Elasticsearch 2.2.0, Logstash 2.2.2, and Kibana 4.4.1.

- `es220_l220_k440`: Elasticsearch 2.2.0, Logstash 2.2.0, and Kibana 4.4.0.

- `E1L1K4`: Elasticsearch 1.7.3, Logstash 1.5.5, and Kibana 4.1.2.

**Note** – See the documentation page for more information on pulling specific combinations of versions of Elasticsearch, Logstash and Kibana.

### Documentation

See the [ELK Docker image documentation web page](http://elk-docker.readthedocs.io/) for complete instructions on how to use this image.

### Docker Hub

This image is hosted on Docker Hub at [https://hub.docker.com/r/sebp/elk/](https://hub.docker.com/r/sebp/elk/).

### About

Written by [Sébastien Pujadas](https://pujadas.net), released under the [Apache 2 license](https://www.apache.org/licenses/LICENSE-2.0).

