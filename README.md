# Speak

Run a slideshow presentation in docker using [Remark](https://github.com/remarkjs/remark)

## 

```
$ ./bin/present [topic/directory]
```

```
docker                               \
  run                                \
  --rm                               \
  -v $PWD:/usr/local/apache2/htdocs/ \
  -p 80:80                           \
  httpd:alpine
```
