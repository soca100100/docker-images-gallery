FROM node:15.14-alpine

WORKDIR /webapp

EXPOSE 3000

COPY package.json package-lock.json ./

RUN npm install --silent

COPY . ./

CMD [ "npm","start" ]