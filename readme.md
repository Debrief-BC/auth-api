# Authentication API

The authentication service for Debrief APIs built on top of [Laravel](https://laravel.com/docs/5.2)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisities

With [PHP](http://php.net/downloads.php), [Composer](https://getcomposer.org/installer), [MySQL](https://www.mysql.com/downloads/), [Redis](http://redis.io/download) and [Git](https://git-scm.com/) installed.

#### Setup Database

Ensure that you have an instance of [MySQL](https;//www.mysql.com) running. [I need help setting up MySQL!](http://dev.mysql.com/doc/refman/5.7/en/installing.html)
```
# Create a database called 'auth'
```

#### Setup Redis

Ensure that you have an instance of [Redis](https;//www.redis.io) running. [I need help setting up Redis!](http://redis.io/download#installation)

Note: The Redis instance is shared between the Auth and Resources (Debrief) API. You don't need to run a second instance if you already started one for the Resources (Debrief) API!
