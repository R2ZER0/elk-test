FROM docker.elastic.co/logstash/logstash:5.5.2
MAINTAINER Rikki Guy <r.guy@mhnltd.co.uk>

# https://www.elastic.co/guide/en/x-pack/current/installing-xpack.html#xpack-uninstalling
RUN logstash-plugin remove x-pack
RUN sed -i '/xpack/d' /usr/share/logstash/config/logstash.yml
