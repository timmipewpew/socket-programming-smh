FROM gcc:9.3
COPY ./src/socket-programming-smh/server
WORKDIR socket-programming/server
RUN gcc -o server server.c
CMD ["./server"]
