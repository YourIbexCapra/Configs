FROM node:18-alpine

RUN mkdir /home/node/app/ && chown -R node:node /home/node/app

ENV NODE_ENV production

WORKDIR /home/node/app

COPY --chown=node:node package*.json ./

USER node

RUN npm install --only=production

COPY --chown=node:node . ./

EXPOSE 80

CMD ["npm", "run", "start:prod"]