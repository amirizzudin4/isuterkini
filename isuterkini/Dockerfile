FROM mhart/alpine-node AS base

RUN mkdir app

COPY ./web/ /app/

# RUN cd app

WORKDIR /app

EXPOSE 3000

CMD npm install && npm start