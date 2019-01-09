# Public Docker image

## Features 

 * PHP 7.2 via deb.sury.org
 * PHP GRPC module
 * PHP Protobuf module
 * Apache mod\_php
 
See also: https://hub.docker.com/r/socialsigninapp/docker-debian-gcp-php72/

## Building

```bash
docker build --build-arg http_proxy=http://192.168.0.66:3128 --build-arg https_proxy=http://192.168.0.66:3128 .
```

## Todo

 * Add checksum checking on the downloaded pecl tgz files.
 * Link better to Debian/Debsury.org so we rebuild on change of those files
