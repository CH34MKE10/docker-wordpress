# docker-wordpress
Spin up your very own wordpress instance in docker

## Setup
Create a [.env](https://docs.docker.com/compose/environment-variables/#the-env-file) file.
This is where you will put the environment variables needed by the wordpress installation.

```bash
touch .env
```
Populate your newly created [.env](https://docs.docker.com/compose/environment-variables/#the-env-file) file(minus the < > symbols).

```bash
MYSQL_ROOT_PASSWORD=<enter_value>
MYSQL_DATABASE=<enter_value>
MYSQL_USER=<enter_value>
MYSQL_PASSWORD=<enter_value>
WORDPRESS_DB_PASSWORD=<enter_value>
```

Ok spin up your new wordpress environment!

```bash
docker-compose up
```
