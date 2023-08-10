FROM alpine:3.16

EXPOSE 3001

WORKDIR /app/back-end

COPY  node_modules.tar.gz /app/back-end/

COPY . /app/back-end/

CMD ["npm", "start"]
