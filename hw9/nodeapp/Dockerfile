FROM node:latest
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
RUN apt-get update
COPY . .
EXPOSE 3000
CMD ["node", "app.js"]
