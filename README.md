# Tiny URl App using Apache Spark and Redis


## Description
TinyURL is a URL shortening service, a web service that provides short aliases for redirection of long URLs.
This Tiny URl  application built with Apache Spark and Redis.
This will run as a stand alone java application which will internally invoke free marker for generating HTML templates  to user.
Redis server is used for manipulating data in data base and can act as in-memory cache.

Tiny URL Home UI Page
=====================

![Tiny URL Home UI Page](https://upload.wikimedia.org/wikipedia/commons/c/c6/TinyURLHomePage.png)


## Dependencies

### Start Redis

Start your redis instance:
```



           _.-``__ ''-._
      _.-``    `.  `_.  ''-._           Redis 2.8.9 (00000000/0) 64 bit
  .-`` .-```.  ```\/    _.,_ ''-._
 (    '      ,       .-`  | `,    )     Running in stand alone mode
 |`-._`-...-` __...-.``-._|'` _.-'|     Port: 6379
 |    `-._   `._    /     _.-'    |     PID: 13499
  `-._    `-._  `-./  _.-'    _.-'
 |`-._`-._    `-.__.-'    _.-'_.-'|
 |    `-._`-._        _.-'_.-'    |           http://redis.io
  `-._    `-._`-.__.-'_.-'    _.-'
 |`-._`-._    `-.__.-'    _.-'_.-'|
 |    `-._`-._        _.-'_.-'    |
  `-._    `-._`-.__.-'_.-'    _.-'
      `-._    `-.__.-'    _.-'
          `-._        _.-'
              `-.__.-'
```              
              
              

Downloads Redis server from

https://github.com/rgl/redis/downloads

This needs to be installed in your machine and Running with port :6379

Note:
Before starting Redis server replace TinyUrlApp/redis.conf  with existing file 
For windows redis.conf will be present in the below directory

C:\Program Files\Redis\conf


Technologies/Frameworks used here :
=================================

- Java
- Spark Java
- Free Marker
- Redis
- Modernizr
- JQuery




## Run

For testing it locally, there's a `TinyURLAppController.java` file included in the `src/com/TinyUrlApp/Controller` folder. 
Open up the java terminal and run the TinyURLAppController.java file ( You need to have **Redis server** installed  before start running java code ).


You can now open your browser: `http://localhost:4567/tinyUrl`


