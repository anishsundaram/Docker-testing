FROM gcc:latest

COPY . /usr/src/test

WORKDIR /usr/src/test

RUN gcc -o test main.cpp

CMD ["./test"]