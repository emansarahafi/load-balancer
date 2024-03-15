FROM node:18.19.0

WORKDIR /app

COPY package.json /app

RUN npm install

ENV MESSAGE=""
ENV DB_HOST=""
ENV DB_USER=""
ENV DB_PASS=""
ENV DB_NAME=""
ENV SERVERNUM=""

COPY . /app

CMD ["npm", "start"]