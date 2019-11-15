FROM node:13.1.0-alpine

WORKDIR /var/www

ADD ./app.js .
ADD ./package.json .
RUN npm i
RUN ls 

CMD ["node",  "/var/www/app.js"]

