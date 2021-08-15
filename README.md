PostgreSQL Exporter-Prometheus-Grafana
========

A monitoring solution for PostgreSQL db with [Prometheus](https://prometheus.io/), [Grafana](http://grafana.org/), [postgresql-exporter](https://github.com/prometheus-community/postgres_exporter).  


Additional info: [Docker - Prometheus and Grafana](https://bogotobogo.com/DevOps/Docker/Docker_Prometheus_Grafana.php)

## Install

### NB:

Grafana admin password in /grafana/config.monitoring:
```
GF_SECURITY_ADMIN_PASSWORD=foobar
```


```bash
docker-compose up -d
```