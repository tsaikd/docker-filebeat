docker-filebeat
===============

Docker image for elastic [filebeat]

# docker-compose sample

```
filebeat:
  image: tsaikd/filebeat:1.1.1
  volumes:
    - ./filebeat/filebeat.yml:/filebeat/filebeat.yml:ro
```

See https://www.elastic.co/guide/en/beats/filebeat/current/index.html for more document about [filebeat]

[filebeat]: https://www.elastic.co/products/beats/filebeat

