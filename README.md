# docker-php
PHP 8 Docker Image

- Alpine Base
- PHP 8
- Composer 2
- XDebug 3

Runs as `1000:www-data`

`WORKDIR` optimised for CaddyServer app at `/srv/app/`.

### Build ENVs

```
ENVIROMENT=production
TZ=UTC
UID=1000
```

`ENVIROMENT` defines weather `development` or `production` php.ini template is used.
