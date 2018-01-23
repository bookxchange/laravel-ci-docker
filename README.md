# Laravel CI

A Docker image based on [php](https://hub.docker.com/_/php/) for CI testing of
the [Laravel](https://github.com/laravel/laravel) framework. Includes proper php
modules (e.g. MySQL and Postgres driver) installation.

The purpose of such image is to reduce the needs to redo all the apt-get updates,
docker-php-ext-install and composer download. In turn should reduce the time
taken for CI testings.
