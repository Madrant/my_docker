FROM debian:latest

RUN apt-get update && apt-get install -y \
    bash-completion \
    bc \
    bsdmainutils \
    curl \
    gawk \
    grep \
    iperf \
    iproute2 \
    mc \
    netcat \
    net-tools \
    net-tools \
    nmap \
    pv \
    sed \
    socat \
    sudo \
    tcpdump \
    telnet \
    wget \
    && rm -rf /var/lib/apt/lists/*

CMD ["/bin/bash"]
