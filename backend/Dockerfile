FROM node:18-alpine

WORKDIR /APP

COPY package*.json ./

RUN nmp install

COPY . .

EXPOSE 5000

CMD ["node", "server.js"]
