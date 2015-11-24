# kafka-test
Small study project on [Apache Kafka](http://kafka.apache.org/) which is publish-subscribe messaging rethought as a distributed commit log. A good read is the book [Unified Log Processing by Alexander Dean](https://www.manning.com/books/unified-log-processing) and the ideas by [Martin Kleppmann's book: Designing Data-Intensive Applications](http://my.safaribooksonline.com/book/software-engineering-and-development/9781491903063), and has [some good talks on Youtube](https://www.youtube.com/channel/UClB4KPy5LkJj1t3SgYVtMOQ) so enjoy!

# Building and launching
This project builds `v9.0.0.0` of Kafka and uses Zookeeper `v3.4.5`. Just execute the `launch.sh` script and all will be build and launched.

# Hello World
The ["helloworld"](http://kafka.apache.org/documentation.html#quickstart_send) of zookeeper is the `console-producer` and `console-consumer` example, in which a producer places a message on the topic `test` and the consumer, consumes the message. In contrast to message brokers, the message will stay persisted after it has been processed by a consumer (the log concept) and will always be available to new consumers that start processing the topic `test` from `the beginning`.

# more to come...
...

# resources
https://github.com/yahoo/kafka-manager