FROM ubuntu:22.04

RUN apt-get update; \
    apt-get install -y curl unzip; \
    cd opt; \
    mkdir pharo; \
    cd pharo; \
    curl -L https://get.pharo.org/64/110+vm  | bash;

ENV PATH=${PATH}:/opt/pharo

ENTRYPOINT ["pharo", "/opt/pharo/Pharo.image"]
