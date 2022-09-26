FROM node:18.2.0-alpine3.14

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 5001

CMD ["npm", "start"]