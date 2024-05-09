FROM node:21-alpine3.17 as build01
WORKDIR /app
COPY package*.json .
RUN npm i  
COPY . .
EXPOSE 3002
CMD [ "npm", "start" ]