#  Real-Time Messaging App


1. Clone this repository
```shell
$ git clone git@github.com:jorgeacetozi/ebook-chat-app-spring-websocket-cassandra-redis-rabbitmq.git
```
2. Setup the dependencies (Cassandra, Redis, MySQL and RabbitMQ with STOMP support)

```shell
$ docker-compose -f docker-compose/dependencies.yml up
```

3. Start the application

```shell
$ wget https://github.com/jorgeacetozi/ebook-chat-app-spring-websocket-cassandra-redis/releases/download/ebook-chat-1.0.0/ebook-chat-1.0.0.jar && java -jar ebook-chat-1.0.0.jar
```
