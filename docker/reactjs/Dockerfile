FROM node:14.9

WORKDIR /var/www/app

COPY package*.json /var/www/app
RUN npm install
COPY . .

EXPOSE 3000

CMD ["npm", "start"]