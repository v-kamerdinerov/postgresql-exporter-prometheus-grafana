PostgreSQL Exporter-Prometheus-Grafana
========

A monitoring solution for PostgreSQL db with [Prometheus](https://prometheus.io/), [Grafana](http://grafana.org/), [postgres-exporter](https://github.com/prometheus-community/postgres_exporter).  


Additional info: [Docker - Prometheus and Grafana](https://bogotobogo.com/DevOps/Docker/Docker_Prometheus_Grafana.php)

* The latest PostgreSQL database image is also included for testing.


## Pre-install

Grafana admin password in `grafana/config.monitoring`
```
GF_SECURITY_ADMIN_PASSWORD=foobar
```

Database configure in `postgres-exporter/config`
```bash
DATA_SOURCE_NAME=postgresql://postgres:password@postgres_db:5432/postgres?sslmode=disable
```

## Quick Start
```bash
docker-compose up -d
```

#### Example dashboard
![Example dashboard](https://i.gyazo.com/6547d7aed4d8b07afb1035fd4133c467.png)

