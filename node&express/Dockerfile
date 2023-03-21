FROM node:14-alpine

WORKDIR /app

ADD package.json .

RUN npm i --silent

ENTRYPOINT ["npm", "run"]

CMD ["start:dev"]