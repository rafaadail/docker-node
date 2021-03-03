FROM node:lts

WORKDIR /var/www/api-nodejs

COPY package.json /var/www/api-nodejs

EXPOSE 3000

##ENV ADB_IP="192.168.110.3"
ENV REACT_NATIVE_PACKAGER_HOSTNAME="192.168.15.19"
ENV HOST="0.0.0.0"

RUN apt-get update
