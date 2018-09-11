FROM node:alpine

WORKDIR /app

COPY ./docker-entrypoint.sh /usr/local/

ENTRYPOINT ["/usr/local/docker-entrypoint.sh"]

CMD [ "node", "index.js" ]