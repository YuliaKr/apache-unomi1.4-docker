# Running Unomi
Unomi requires ElasticSearch so it is recommended to run Unomi and ElasticSearch using docker-compose:
```
docker-compose up
```

# Environment variables

When you start the `unomi` image, you can adjust the configuration of the Unomi instance by passing one or more environment variables on the `docker run` command line.

- **`ELASTICSEARCH_HOST`** - The IP address of hostname for ElasticSearch
- **`ELASTICSEARCH_PORT`** - The port for ElasticSearch
