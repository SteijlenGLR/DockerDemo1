# Skeleton Project to start PHP IDE environment with Docker.

This project is available to be able to quickly setup a local docker environment to be able to start development in PHPStorm quickly.
The skeleton will set-up a project with 4 docker containers:

1.  NGINX as de HTTP Reverse Proxy Server (Configured through nginx.conf).
2.  PHP-FPN (PHP:8.2.3) PHP processor, will handle all .php requests. (configured through the php-dockerfile).
3.  MariaDB as an opensource alternative to the MySQL Database server.
4.  PHPMyAdmin an opensource web-based MySQL admin panel (Accessible on localhost:8081 user root and password as mentioned in the docker-compose.yml file).

PHP Source files should go into the src directory.
