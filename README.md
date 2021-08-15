PostgreSQL Exporter-Prometheus-Grafana
========

A monitoring solution for PostgreSQL db with [Prometheus](https://prometheus.io/), [Grafana](http://grafana.org/), [postgresql-exporter](https://github.com/prometheus-community/postgres_exporter).  


Additional info: [Docker - Prometheus and Grafana](https://bogotobogo.com/DevOps/Docker/Docker_Prometheus_Grafana.php)


## Install

Grafana admin password in `grafana/config.monitoring`
```
GF_SECURITY_ADMIN_PASSWORD=foobar
```


### DB
Database configure in `postgres-exporter/config`
```bash
DATA_SOURCE_NAME=postgresql://postgres:password@postgres_db:5432/postgres?sslmode=disable
```

## Quick Start
```bash
docker-compose up -d
```