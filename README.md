# rabbitmq-producer-consumer-tutorial


This code is based in youtube tutorial

https://www.youtube.com/watch?v=Wiw7oOgBjFs&list=PLL2hlSFBmWwy8lhnj11FVJldKsZm66oq1&index=3&ab_channel=soumilshah1995

Thanks soumilshah1995 for share this tutorial series

Docker rabbitmq

docker run --rm -it --hostname rabbit-container -p 15672:15672 -p 5672:5672 rabbitmq:3-management



The port 5672 is used for the RabbitMQ client connections, and the port 15672 is for the RabbitMQ management website
http://localhost:15672


username and password of guest / guest