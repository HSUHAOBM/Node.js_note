FROM node:13

WORKDIR /usr/app
COPY package.json .
RUN npm install --quiet
COPY . .

EXPOSE 3310
CMD [ "node", "index.js" ]
