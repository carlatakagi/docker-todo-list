FROM node:14-alpine

WORKDIR /app

ADD node_modules.tar.gz .

COPY package.json ./

RUN npm install

EXPOSE 3000

CMD ["npm", "start"]