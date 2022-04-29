FROM node:14.19.1-alpine

WORKDIR /usr/src/frontend

ENV PATH /usr/src/node_modules/.bin:$PATH

COPY package.json .

RUN npm install --silent

COPY . /usr/src/frontend

# RUN npm install react-scripts@3.0.1 -g --silent

EXPOSE 3000

CMD npm start