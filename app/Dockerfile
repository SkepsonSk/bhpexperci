FROM node
WORKDIR /usr/src/app
COPY . /usr/src/app

RUN npm install
RUN npm run build

CMD node build/index.js
