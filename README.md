# leleko-gogs
Test docker-compose with gogs app

Please change passwords in .env file

## Default access params:

### Gogs app website:
http://localhost:3000/

### phpmyadmin website:
http://localhost:888

mariadb root password is 123456
mariadb maria_user password is 654321

For launch type in terminal "docker-compose -p "leleko-gogs" up --abort-on-container-exit --exit-code-from gogs-local"

First open Gogs app website is launch Gogs installation.
replace localhost:3306 -> db:3306 in mysql host field.
