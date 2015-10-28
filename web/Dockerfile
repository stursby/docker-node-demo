FROM node:4.2

RUN npm install babel nodemon -g

ADD package.json /web/
WORKDIR /web
RUN npm install
#ADD . /web

#CMD ["babel-node", "server.js"]

CMD ["nodemon", "--exec", "npm", "run", "babel-node", "--", "server.js"]
