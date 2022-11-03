FROM node:16

WORKDIR /nova-api
COPY package.json .
RUN npm install
COPY . .
CMD npm start
