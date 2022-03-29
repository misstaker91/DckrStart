FROM node:17
WORKDIR /user/src/app
COPY ./package.json ./
COPY node_modules/uri-js/yarn.lock ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]