FROM grafana/grafana-enterprise:latest
COPY glances-for-flux_rev4.json /var/lib/grafana/dashboards/glances-for-flux_rev4.json
COPY grafana.ini /etc/grafana/grafana.ini
COPY datasource.yaml /etc/grafana/provisioning/datasources/datasource.yaml
COPY dashboard.yaml /etc/grafana/provisioning/dashboards/dashboard.yaml

