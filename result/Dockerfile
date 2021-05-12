FROM node:12-alpine

WORKDIR /result
COPY ./ ./
EXPOSE 80

RUN npm install
RUN npm audit fix

CMD ["node", "server.js"]