FROM node:23-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install
RUN npm install nodemon

COPY . .

EXPOSE 8800

CMD ["npm", "start"]