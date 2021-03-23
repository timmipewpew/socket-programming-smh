FROM gcc:9.3
COPY ./src/socket-programming-smh/client
WORKDIR socket-programming/client
RUN gcc -o server server.c
CMD ["./server"]
