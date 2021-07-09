# Extremely simple prometheus stack

A very simple prometheus/grafana stack.

## Overview
 - [Prometheus server](https://prometheus.io/docs/prometheus/latest/installation/)
 - [Node exporter container](https://github.com/prometheus/node_exporter)
 - [Grafana](https://grafana.com/docs/grafana/latest/installation/docker/)

## Requirements
  - Docker
  - docker-compose

## Configure Grafana
![Prometheus config](./image/prometheus_config.png)
 - go to configuration -> data sources
 - Add data source
 - Find the following configs and set them to the values below (as shown in image)
    * URL: http://127.0.0.1:9090
    * Access: Browser (this is set to server by default)
 - Save & test

## Web UI(s)
 - Prometheus: 127.0.0.19090
 - node_exporter: 127.0.0.19000
 - grafana: 127.0.0.13000
