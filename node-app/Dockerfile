FROM node:12
LABEL MAINTAINER="Ade Mahmud <ademahmud.media@gmail.com>"

WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install

COPY app ./

EXPOSE 8080
CMD [ "node", "server.js" ]