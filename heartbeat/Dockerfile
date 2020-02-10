ARG ELK_VERSION

FROM docker.elastic.co/beats/heartbeat:${ELK_VERSION}

# Log to stderr and disable syslog/file output and
# passing heartbeat data to the Uptime App in Kibana
RUN /usr/share/heartbeat/heartbeat setup -e
