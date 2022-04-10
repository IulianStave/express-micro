# FROM node:16.5.0-alpine
FROM node:16-alpine

WORKDIR /app
COPY package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]
