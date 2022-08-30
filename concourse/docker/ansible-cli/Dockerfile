FROM ubuntu:22.04
RUN apt update; \
    apt install -y openssh-client; \
    apt install -y python3; \
    apt install -y python3-pip; \
    apt install -y wget; \
    pip3 install --upgrade pip; \
    pip3 install --upgrade virtualenv; \
    python3 -m pip install ansible; \