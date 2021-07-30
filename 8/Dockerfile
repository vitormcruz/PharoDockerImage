FROM ubuntu:18.04

RUN apt-get update; \
    apt-get install -y curl unzip libgit2-dev; \
    cd opt; \
    mkdir pharo; \
    cd pharo; \
    curl -L https://get.pharo.org/64/80+vm  | bash;

ENTRYPOINT ["./pharo", "/Pharo.image"]
