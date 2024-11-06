FROM node:lts-alpine

WORKDIR '/app'

COPY package.json .

RUN yarn install --loglevel verbose

COPY . .

CMD ["npm", "run", "start"]
