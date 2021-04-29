FROM node:14.15.4-alpine3.12

WORKDIR /APP

COPY package*.json ./

RUN npm ci

COPY . .

EXPOSE 8080

CMD ["node", "app.js"]

