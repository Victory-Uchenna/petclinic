FROM node:current-slim

WORKDIR /usr/src/app

RUN npm install -g @angular/cli@8.0.3


COPY . /usr/src/app

RUN npm install --save-dev @angular/cli@8.0.3

RUN rm -f package-lock.json 

RUN npm install 

CMD ng serve --host 0.0.0.0 --port 4200
