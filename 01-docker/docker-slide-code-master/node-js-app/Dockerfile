FROM alpine
LABEL maintainer="aamirpinger@yahoo.com"
RUN apk add --update nodejs nodejs-npm
COPY . /src
WORKDIR /src
RUN npm install
ENV CREATEDBY="Muhammza Hamza Hanif"
EXPOSE 8080
ENTRYPOINT ["node", "./app.js"]
