FROM ubuntu:20.04

COPY package.json /app/
COPY src /app/src

WORKDIR /app

RUN npm install

CMD [ "node", "app.js" ]

