# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash:5.6.2

USER root
RUN mkdir /consumption
RUN chown logstash.logstash /consumption
USER logstash
# Add your logstash plugins setup here
RUN logstash-plugin install logstash-filter-alter
