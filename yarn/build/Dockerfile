FROM node:alpine

RUN apk update && \
    apk add yarn openssh && \
    rm -rf /var/cache/apk/*

WORKDIR /web

ENTRYPOINT ["tail", "-f", "/dev/null"]