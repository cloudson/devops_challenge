FROM node:13.1.0-alpine

WORKDIR /app

COPY . /app
RUN npm i

EXPOSE $APP_PORT

CMD ["npm", "start"]

