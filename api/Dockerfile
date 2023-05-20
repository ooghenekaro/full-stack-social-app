FROM node:lts-alpine3.17

WORKDIR /app

COPY package*.json /app

RUN yarn install

COPY . .

ENV NODE_ENV=production


CMD [ "yarn", "start" ]
