FROM node:18-apline

WORKDIR /APP

COPY package*.json ./

RUN nmp install

COPY . .

EXPOSE 5000

CMD ["node", "server.js"]
