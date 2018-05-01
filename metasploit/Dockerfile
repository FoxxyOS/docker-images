FROM foxxy-core:latest
MAINTAINER Lorenzo "Palinuro" Faletra (palinuro@linux.it)
ENV DEBIAN_FRONTEND noninteractive

# Install components
RUN apt-get update; apt-get -y dist-upgrade;
RUN apt-get -y --no-install-recommends install foxxy-menu
RUN apt-get -y install foxxy-pico metasploit-framework postgresql

ENTRYPOINT msfconsole-start $@
