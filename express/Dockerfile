FROM node:lts AS builder

WORKDIR /app

COPY package.json .
RUN npm install

COPY . .

EXPOSE 8080
CMD [ "node",'index.js' ]

