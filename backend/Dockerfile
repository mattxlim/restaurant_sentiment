FROM node:13-alpine

WORKDIR /app

COPY package*.json ./

COPY yarn.lock ./

RUN yarn install

COPY . .

CMD ["yarn", "dev"]