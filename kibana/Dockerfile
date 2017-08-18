FROM docker.elastic.co/kibana/kibana:5.5.1

COPY kibana.yml /usr/share/kibana/config/kibana.yml

RUN bin/kibana-plugin remove x-pack