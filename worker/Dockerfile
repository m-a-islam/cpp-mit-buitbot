FROM buildbot/buildbot-worker
USER root
RUN apt-get update \
 && apt-get install -y --no-install-recommends g++ make git \
 && rm -rf /var/lib/apt/lists/*
USER buildbot

