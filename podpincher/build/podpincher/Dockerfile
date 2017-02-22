FROM ruby:2.2.2-onbuild
RUN apt-get -y update && \
    DEBIAN_FRONTEND=noninteractive apt-get -y install nodejs && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*
CMD ["dashing", "start", "-p", "4567", "-e", "production", "-t", "90"]
