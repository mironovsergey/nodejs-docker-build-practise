FROM node:16-alpine

WORKDIR /home/ilovedocker/app

COPY ./packages/package*.json ./

RUN npm install --omit=dev

COPY ./src/ ./

EXPOSE 3032

CMD ["node", "main.js"]