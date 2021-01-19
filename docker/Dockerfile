FROM alpine as BUILD
RUN apk add --no-cache netcat-openbsd
RUN mkdir /netct

ADD server.sh /netct/server.sh 
VOLUME /netct
CMD bin/sh netct/server.sh

