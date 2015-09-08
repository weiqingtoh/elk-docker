# Elasticsearch, Logstash, Kibana (ELK) Docker images

The repo contains separate Docker images for the setup of ELK. The containerisation of each tool provides modularity for easy modifications to future logging setups. 

This is still a work in progress and credit goes to the author of the original repo, [Sébastien Pujadas](https://pujadas.net).

To modify, please run the following commands, where `{tool}` is either elasticsearch, logstash or kibana:

```
cp docker-compose-sample.yml ./{tool}/docker-compose.yml
cp Dockerfile-sample ./{tool}/Dockerfile
```

# Original Readme

## Elasticsearch, Logstash, Kibana (ELK) Docker image

[![](https://badge.imagelayers.io/sebp/elk:latest.svg)](https://imagelayers.io/?images=sebp/elk:latest 'Get your own badge on imagelayers.io')

This Docker image provides a convenient centralised log server and log management web interface, by packaging Elasticsearch (version 1.7.1), Logstash (version 1.5.4), and Kibana (version 4.1.1), collectively known as ELK.

### Documentation

See the [ELK Docker image documentation web page](https://spujadas.github.io/elk-docker) for complete instructions on how to use this image.

### About

Written by [Sébastien Pujadas](https://pujadas.net), released under the [Apache 2 license](https://www.apache.org/licenses/LICENSE-2.0).