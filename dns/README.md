# Talks!

To start a talk clone this repo and serve the files:

```
docker                               \
  run                                \
  --rm                               \
  -v $PWD:/usr/local/apache2/htdocs/ \
  -p 80:80                           \
  httpd:alpine
```
