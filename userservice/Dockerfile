FROM node:14.15.0-alpine3.10

WORKDIR /usr/share/app

COPY package.json package.json

RUN npm install

COPY userservice/server.js userservice/server.js

EXPOSE 4000

CMD ["npm", "run", "start:userservice"]