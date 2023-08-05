### Run example

```
docker run \
  -it \
  --rm \
  --name my-running-script \
  -v "$PWD":/usr/src/myapp \
  -w /usr/src/myapp php:8.1.12-cli-alpine /bin/sh -c "./composer.phar install && php example.php"
```


```
docker run \
  -it \
  --rm \
  --name my-running-script \
  -v "$PWD":/usr/src/myapp \
  -w /usr/src/myapp php:8.1.13-cli-alpine /bin/sh -c "./composer.phar install && php example.php"
```
