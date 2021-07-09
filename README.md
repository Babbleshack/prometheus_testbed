# Extremely simple prometheus stack

## Overview
 - Prometheus server
 - [Node exporter container](https://github.com/prometheus/node_exporter)
 - Grafana

## Configure Grafana
![Prometheus config](./image/prometheus_config.png)
 - go to configuration -> data sources
 - Add data source
 - Find the following configs and set them to the values below (as shown in image)
    * URL: http://localhost:9090
    * Access: Browser (this is set to server by default)
 - Save & test

