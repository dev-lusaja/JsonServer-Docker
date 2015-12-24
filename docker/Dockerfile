FROM node:5.3.0

MAINTAINER Dev-Lusaja <janoone52@gmail.com>

RUN mkdir -p /srv/www/json-server/

WORKDIR /srv/www/json-server

RUN npm install json-server -g

CMD ["json-server", "/srv/www/json-server/db/db.json"]