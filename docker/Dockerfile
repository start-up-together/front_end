# base
FROM node:16.15-alpine3.15 AS base

RUN apk add --update --no-cache bash

WORKDIR /var/www/html

RUN npm install -g create-react-app && npm init react-app my-app

WORKDIR /var/www/html/my-app

ENTRYPOINT [ "npm", "start" ]
