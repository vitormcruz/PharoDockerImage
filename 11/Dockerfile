FROM ubuntu:18.04

RUN apt-get update; \
    apt-get install -y curl unzip libgit2-dev zlib1g; \
    cd opt; \
    mkdir pharo; \
    cd pharo; \
    curl -L https://get.pharo.org/64/110+vm  | bash;

ENV PATH=${PATH}:/opt/pharo

ENTRYPOINT ["pharo", "/opt/pharo/Pharo.image"]
