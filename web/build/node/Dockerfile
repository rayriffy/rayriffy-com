FROM node:alpine

WORKDIR /app

COPY ./docker-entrypoint.sh /usr/local/bin/

ENTRYPOINT ["docker-entrypoint.sh"]

CMD [ "node", "index.js" ]