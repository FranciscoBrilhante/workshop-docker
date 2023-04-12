FROM node:18

RUN apt-get update -y
WORKDIR /usr/src/app
COPY . .
WORKDIR /usr/src/app/
RUN npm install

CMD npm start