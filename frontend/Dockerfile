FROM node:18-alpine
WORKDIR /usr/src
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8082
CMD [ "npm", "start" ]
