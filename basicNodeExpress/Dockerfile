FROM node:boron

#Create app directory
WORKDIR /usr/src/app

#Install app dependencies
COPY package.json .

RUN npm install

#Bundle source code inside docker image
COPY . .

EXPOSE 8080

CMD [ "npm", "start" ]
