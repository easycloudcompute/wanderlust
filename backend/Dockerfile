FROM node:latest

WORKDIR /app

COPY . .

RUN npm i

COPY .env.sample .env

EXPOSE 500

CMD [ "npm" , "start" ]
