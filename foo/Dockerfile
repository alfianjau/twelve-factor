FROM node:12-alpine
WORKDIR /srv
COPY . .
RUN yarn install --production
CMD [ "node", "index.js" ]
