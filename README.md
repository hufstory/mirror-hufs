# Mirror Hufs

## Requirement

### Host setup

- [Docker Engine](https://docs.docker.com/install/) version **19.03** or newer
- [Docker Compose](https://docs.docker.com/compose/install/) version **1.27.2** or newer

### Host Port

- 5000: Logstash TCP input
- 9200: Elasticsearch HTTP
- 9300: Elasticsearch TCP transport
- 5601: Kibana

### Github Secret

- SSH_HOST
- SSH_KEY
- SSH_USERNAME
- DEFAULT_EMAIL

### Enviorment

## Inital Setup

### Setting up user authentication

The stack is pre-configured with the following **privileged** bootstrap user:

- user: _elastic_
- password: _changeme_
