FROM foxxy-core:latest
MAINTAINER Lorenzo "Palinuro" Faletra (palinuro@linux.it)
ENV DEBIAN_FRONTEND noninteractive

# Install components
RUN apt-get update; apt-get -y dist-upgrade
RUN apt-get -y install foxxy-pico
RUN apt-get -y install foxxy-mini foxxy-tools-cloud

ENTRYPOINT bash $@
