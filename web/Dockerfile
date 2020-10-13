FROM node:12-alpine
 
WORKDIR /app

ENV NODE_ENV=developer
 
EXPOSE 3000

RUN mkdir /app && \
    yarn global add nodemon

CMD yarn install && \
    yarn start