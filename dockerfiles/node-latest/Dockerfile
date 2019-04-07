FROM node:latest
RUN apt-get update && \
    apt-get install -y default-jre && \
    apt-get clean && \
    apt-get -y autoremove && \
    apt-get -y clean && \
    rm -rf /var/lib/apt/lists/*
CMD tail -f /dev/null
