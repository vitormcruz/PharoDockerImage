FROM ubuntu:18.04

RUN apt-get update; \
    apt-get install -y curl unzip libgit2-dev; \
    curl -L https://get.pharo.org/64 | bash;

#ENTRYPOINT ["./pharo", "/Pharo.image", "--list"]
