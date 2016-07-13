Defcon's Drupal 7.x PHP 5.x
=============

Readme file

Docker stuff
------------

### Environment variables

* DB_USER
  - Database username, **required**

* DB_PASS
  - Database password, **required**

* HTTP_AUTH_USER
  - HTTP authentication username (optional)

* HTTP_AUTH_PASS
  - HTTP authentication password (optional)

### Ports

* 80
  - The web GUI (should probably be exposed)

* 3306
  - The database (should also probably be exposed)

* 22
  - SSH access, user: root, password: root (should definitely *not* be exposed)
