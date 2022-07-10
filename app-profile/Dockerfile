FROM node:13-alpine

ENV MONGO_INITDB_ROOT_USERNAME=admin \
    MONGO_INITDB_ROOT_PASSWORD=mongopass

RUN mkdir -p /home/app

COPY . /home/app

CMD ["node", "/home/app/server.2.0.js"]

