FROM node:10.15.3-alpine

WORKDIR /bot

COPY . /bot

RUN apk add --no-cache make gcc g++ python3 ; \
  npm install --production --silent ; \
  apk del make gcc g++ python3
