FROM node:14.19.1-alpine3.14

WORKDIR /usr/src/backend

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 5000

CMD ["node", "server.js"]

