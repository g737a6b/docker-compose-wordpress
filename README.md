# docker-compose-wordpress

```sh
wget https://ja.wordpress.org/wordpress-4.9.6-ja.zip
unzip wordpress-4.9.6-ja.zip
rm wordpress-4.9.6-ja.zip
cp wordpress/wp-config-sample.php wordpress/wp-config.php
vi wordpress/wp-config.php
docker-compose up -d
```
