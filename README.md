FROM node:8.4.0
WORKDIR /siri
COPY . .
RUN npm install
