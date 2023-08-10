FROM alpine:3.16

EXPOSE 3000

WORKDIR /app/front-end

COPY node_modules.tar.gz /app/front-end/

COPY . /app/front-end/

CMD ["npm", "start"]
