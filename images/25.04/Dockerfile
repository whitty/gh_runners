ARG BASE=25.04
FROM ubuntu:${BASE}

RUN apt-get update && env DEBIAN_FRONTEND=noninteractive \
    apt-get install -y --no-install-recommends \
    build-essential \
    lsb-release \
    curl ca-certificates \
    devscripts equivs \
    git && apt-get clean && rm -rf /var/lib/apt
