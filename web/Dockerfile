FROM node:18

WORKDIR /usr/src/app

COPY package*.json .

RUN npm install

COPY . .

ENV PORT=3001 \
    API_HOST=http://3.149.1.122:3000

EXPOSE 3000

CMD ["npm","start"]


