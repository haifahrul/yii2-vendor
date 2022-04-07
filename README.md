
# Composer install with Docker
```
docker run --rm --interactive --tty \
  --volume $PWD:/app \
  composer install \
  --ignore-platform-req=ext-gd
```
