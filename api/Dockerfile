FROM node:16-alpine3.16

WORKDIR /api

COPY package.json .
COPY package-lock.json .

RUN npm i

COPY . .

CMD ["npm", "run", "start"]