FROM alpine:3.15

EXPOSE 3001

WORKDIR /app

ADD node_modules.tar.gz .

COPY . .

CMD [ "npm", "start" ]
