# docker-compose-wordpress

```
docker run -it --rm -v $(pwd):/app composer:1.6 run-script wp-install
cp wordpress/wp-config-sample.php wordpress/wp-config.php
vi wordpress/wp-config.php
docker-compose up -d
```
