FROM node:14-alpine

WORKDIR /bezkoder-api
COPY package.json .
RUN npm install
COPY . .
EXPOSE 8080
CMD npm start