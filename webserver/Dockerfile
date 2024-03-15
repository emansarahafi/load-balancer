FROM node:18.19.0

WORKDIR /app

COPY . .

RUN npm install

ENV MESSAGE ""
ENV DB_HOST ""
ENV DB_USER ""
ENV DB_PASS ""
ENV DB_NAME ""
ENV SERVERNUM ""


EXPOSE 3030

CMD ["npm", "start"]

## docker build -t web-server .

## docker run -e MESSAGE="TEST Hello World" -p 3030:3030 --name web-test web-server