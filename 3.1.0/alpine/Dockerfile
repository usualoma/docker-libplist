FROM alpine:3.8

RUN set -ex \
    \
    && echo "@testing http://dl-cdn.alpinelinux.org/alpine/edge/testing" >> /etc/apk/repositories \
    && apk add --update --no-cache libplist@testing \
    && rm -rf /tmp/* /var/tmp/* /var/cache/apk/*
