FROM node:18-alpine

WORKDIR /APP

COPY package*.json ./

RUN nmp install

COPY . .
EXPOSE 3000

CMD ["npm", "start"]
