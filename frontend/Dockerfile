FROM node:10

WORKDIR /usr/src/app/frontend

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 4000

CMD ["npm", "start"]