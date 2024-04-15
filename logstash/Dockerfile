ARG ELASTIC_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${ELASTIC_VERSION}

COPY mysql-connector-j-8.3.0/mysql-connector-j-8.3.0.jar /usr/share/logstash/logstash-core/lib/jars/mysql-connector-j-8.3.0.jar

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
