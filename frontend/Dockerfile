FROM node:alpine

WORKDIR /app/frontend

COPY . .


RUN npm install

RUN apk update && apk add bash

RUN npm run dev
COPY . .

EXPOSE 3000



# CMD ["npm", "run", "dev"]