
FROM node:14-alpine

WORKDIR /app

COPY package.json package-lock.json ./

ADD ./node_modules.tar.gz .

RUN npm install

COPY . .

CMD ["npm", "test"]