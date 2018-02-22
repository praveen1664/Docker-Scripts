FROM ubuntu
RUN apt-get upgrade -y && apt-get update -y
RUN apt-get install rabbitmq-server -y
EXPOSE 5672 15672 25672 4369 9100 9101 9102 9103 9104 9105
ENTRYPOINT rabbitmq-server start
