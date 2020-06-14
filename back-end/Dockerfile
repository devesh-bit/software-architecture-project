FROM node:10

WORKDIR /usr/app.js

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 4000

CMD [ "npm", "start" ]
