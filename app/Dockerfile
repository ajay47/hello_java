FROM node:4-onbuild

MAINTAINER Ajay <ajayc2010@gmail.com>

ADD . /var/www/srv

WORKDIR /var/www/srv

RUN npm install

CMD ["nodejs","app.js"]

RUN chmod +x ./test/test.sh

RUN ./test/test.sh


