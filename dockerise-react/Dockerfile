FROM mhart/alpine-node:11 AS builder
WORKDIR /app
COPY package.json /app
RUN npm install

COPY . /app

CMD ["npm","start"]