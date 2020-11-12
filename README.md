# Smithsoft PHP-FPM Container

Container derived from:

* PHP:7.4-fpm
* [With extensions](https://floor12.net/en/blog/perfect-php-fpm-image.html)

### Local workspace

Add this line to the end of `/etc/hosts` file:

```
127.0.0.1   php-docker.local
```

Then check out this repo & run the `docker-compose.yml` file to get a production PHP environment.

```console
$ git clone git@github.com:Smithsoft/php-fpm.git
$ docker-compose up
```

Now you should be able load up [php-docker.local:8080](http://php-docker.local:8080) to view the site.