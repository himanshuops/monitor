# Monitoring Stack with Docker Compose

This repository contains a Docker Compose setup for a monitoring stack consisting of Grafana, Loki, Promtail, Prometheus, and Node Exporter.

## Usage

1. Clone this repository:

```bash
git clone https://github.com/yourusername/yourmonitoringrepo.git
cd yourmonitoringrepo

2- Run the monitoring stack using Docker Compose:
$ docker-compose up -d

Access Grafana at http://localhost:3000. The default username and password are admin/adminadmin@123.

Configure data sources in Grafana to point to Prometheus and Loki.

Explore and visualize your metrics and logs in Grafana!

Promtail Configuration
You can customize Promtail's configuration by modifying the promtail-config.yaml file.
Make sure to replace your_actual_ip with localhost or 127.0.0.1 in the configuration file.
Ports Used
Grafana: 3000
Loki: 3100
Promtail: 9080
Prometheus: 9090
Node Exporter: 9100


Make sure to replace `yourusername` with your GitHub username and `yourmonitoringrepo` with the name of your repository. This README will provide users with clear instructions on how to set up and configure the monitoring stack.
