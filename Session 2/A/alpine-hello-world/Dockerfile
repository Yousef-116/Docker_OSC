FROM docker.io/library/alpine-gcc

COPY main.cpp /usr/hello-world/

WORKDIR /usr/hello-world

RUN apk add --no-cache g++

RUN g++ -o Main main.cpp

CMD ["./Main"]