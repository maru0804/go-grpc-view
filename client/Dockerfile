FROM node:14.15.0-alpine
WORKDIR /client
COPY . .
RUN apk update 
RUN npm install 
RUN npm install -g npm
CMD [ "/bin/sh" ]