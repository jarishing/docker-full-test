FROM node:latest

RUN mkdir -p /usr/src/app/backend
WORKDIR /usr/src/app/backend
COPY . /usr/src/app/backend
RUN npm install
EXPOSE 8080
CMD ["node","server.js"]