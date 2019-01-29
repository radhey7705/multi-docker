FROM node:alpine

WORKDIR '/complex'

COPY ./package.json ./

RUN npm install

COPY . .

CMD ["npm", "run", "start"]