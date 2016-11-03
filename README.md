# alpine-php56
Alpine-based PHP 5.6

## PHP Modules

apc | apcu | bcmath | bz2 | Core | ctype | curl | date | dom | ereg | exif | fileinfo
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |---
filter | gd | gettext | hash | iconv | intl | json | libxml | mbstring | mcrypt | memcache | mysql
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |---
mysqli | mysqlnd | openssl | pcntl | pcre | PDO | pdo_mysql | pdo_pgsql | pdo_sqlite | Phar | posix | readline
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |---
Reflection | session | SimpleXML | soap | SPL | standard | tokenizer | xdebug | xml | xmlreader | xmlrpc | xmlwriter
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |---
xsl | zip | zlib | xdebug |  |  |  |  |  |  |  | 


## TINI

Tini - A tiny but valit `init` for containers

Tini is the simplest `init` you could think of. All Tini does is spawn a single child (Tini is meant to be run in a container), and wait for it to exit all the while reaping zombies and performing signal forwarding.


