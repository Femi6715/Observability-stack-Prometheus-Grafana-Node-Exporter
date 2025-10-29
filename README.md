# compose-prometheus-grafana

Monitoring stack using Docker Compose: **Prometheus**, **Node Exporter**, **Grafana**, with a basic alert rule.

## Run

```bash
docker compose up -d
# Prometheus: http://localhost:9090
# Node Exporter metrics: http://localhost:9100/metrics
# Grafana (admin/admin): http://localhost:3000
```
