FROM ubuntu:24.04

## build
# docker build -t joonlee0228/ubuntu:24.04 .
# docker run joonlee0228/ubuntu:24.04
# docker ps -a | grep ubuntu

# CMD ["echo", "hello"]

## CMD override
# docker run joonlee0228/ubuntu:24.04
# hello
# docker run joonlee0228/ubuntu:24.04 echo world
# world

## Override ENTRYPOINT
# docker run joonlee0228/ubuntu:24.04
# hello
# docker run joonlee0228/ubuntu:24.04 world
# hello world


ENTRYPOINT [ "echo", "hello" ]
CMD ["world"]

## ENTRYPOINT & CMD
# docker run joonlee0228/ubuntu:24.04
# hello world
