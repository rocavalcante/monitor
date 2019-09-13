FROM prom/prometheus:v2.5.0
# https://hub.docker.com/r/prom/prometheus/tags/


COPY conf /etc/prometheus/

CMD        [ "--config.file=/etc/prometheus/prometheus.yml", \
             "--storage.tsdb.path=/prometheus" ]
