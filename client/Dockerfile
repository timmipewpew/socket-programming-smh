FROM gcc:9.3
COPY ./src/socket-programming-smh/client /socket-programming/client/
WORKDIR /socket-programming/client/
RUN gcc -o client client.c
CMD ["./client"]
