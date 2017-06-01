FROM docker.elastic.co/logstash/logstash:5.4.0

COPY logstash.yml /usr/share/logstash/config/logstash.yml

RUN /usr/share/logstash/bin/logstash-plugin remove x-pack