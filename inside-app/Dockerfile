FROM node:14

WORKDIR /inside-app
COPY package.json .
RUN npm install
COPY . .
CMD npm start