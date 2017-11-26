FROM haproxy:1.7-alpine

MAINTAINER Tom Ammon <thomasammon@gmail.com>

RUN apk add --update openssl
RUN apk add --update tcpdump

VOLUME /usr/local/etc/haproxy/haproxy.cfg
