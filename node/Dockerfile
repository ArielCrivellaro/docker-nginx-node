FROM node:15

WORKDIR /usr/src/app

COPY . .

COPY wait-for-it.sh /wait-for-it.sh
RUN chmod +x /wait-for-it.sh

RUN npm install

EXPOSE 3000

CMD [ "node", "app.js" ]