# manticoresearch

This is repository for Manticore (formerly Sphinx) search indexer configuration.

## Usage

Place the files in `/etc/manticoresearch`.

## Configuration

Database configuration is expected in `config.inc.php`.

```php
#!/usr/bin/php

<?php
  echo '
    sql_host = localhost
    sql_user = ab
    sql_pass = ab
    sql_db   = animebytes
    sql_sock = /run/mysqld/mysqld.sock
    sql_port = 3306
  ';
```
