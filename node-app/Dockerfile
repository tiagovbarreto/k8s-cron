FROM node:16.14-alpine

WORKDIR /app
COPY package.json ./
RUN npm install
RUN npm build
COPY ./build ./

CMD ["node", "index.js"]

