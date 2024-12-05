# Simulating Databse outage response

**MongoDB Exporter**: collects metrics from MongoDB and sends them to Prometheus. \
**Prometheus**: Scrapes metrics from the database.\
**Alert Manager**: fire an alert to a slack channel if the database container is down for more than 1 minute.\
**Slack**: receives an alert from Prometheus.\
**Grafana**: Visualizes the database uptime.\
