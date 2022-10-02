FROM node:14.15.0-alpine3.10

WORKDIR /usr/share/app

COPY package.json package.json

RUN npm install

COPY app/server.js app/server.js

EXPOSE 3000

CMD ["npm", "run", "start:app"]