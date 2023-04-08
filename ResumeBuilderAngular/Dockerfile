FROM node:18-alpine

RUN mkdir /opt/frontend

COPY . /opt/frontend

WORKDIR /opt/frontend

RUN npm install --force

#RUN ng build

RUN npm install -g @angular/cli


CMD [ "npm", "start" ]
