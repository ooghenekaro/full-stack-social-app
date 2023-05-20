FROM node:lts-alpine3.17

WORKDIR /app

COPY package*.json /app

RUN yarn install

COPY . .

ENV NODE_ENV=production
ENV MONGO_URL = mongodb+srv://ooghenekaro:D30Jsdg8aYGfw2sJ@kudos-cluster.othz6ca.mongodb.net/bobo?retryWrites=true&w=majority


CMD [ "yarn", "start" ]
