# docker-php7.0-apache
Docker image with old php 7.0 running on apache2 with usual php extensions:

- php7.0
- php7.0-bcmath
- php7.0-mcrypt
- php7.0-mbstring
- php7.0-mysql
- php7.0-sqlite3
- php7.0-soap
- php7.0-xml
- php7.0-zip
- php7.0-xdebug

Based on Debian stretch

# sample usage
`docker run -d -v /var/www/html:/var/www/html -p 8000:80 alcalbg/php7.0-apache`

visit http://localhost:8000/
