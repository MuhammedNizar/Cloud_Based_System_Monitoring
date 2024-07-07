# Monitoring and Visualizing REST API Performance with Prometheus and Grafana on AWS

In modern web development, monitoring and visualizing application performance is essential. This guide provides a brief overview of setting up a monitoring and visualization system for a REST API using Prometheus and Grafana, deployed on AWS.

## Architecture Overview

### AWS Infrastructure:
- **EC2 Instance:** Hosts Prometheus, Grafana, and REST API endpoints.

### Key Components:
- **Prometheus:** Pulls metrics from REST API endpoints and pushes alerts.
- **Grafana:** Queries Prometheus for metrics data and visualizes it in dashboards.
- **Ballerina Endpoints:** REST API endpoints for Prometheus to pull metrics from.

## Steps to Set Up

### Set Up AWS EC2 Instance
1. Launch an EC2 instance.
2. Install Docker and Docker Compose.

### Deploy Ballerina Endpoints
1. Deploy REST API endpoints.
2. Ensure accessibility at specified URLs.

### Install and Configure Prometheus
1. Create a `prometheus.yml` configuration file.
2. Run Prometheus using Docker.

### Install and Configure Grafana
1. Run Grafana using Docker.
2. Configure Grafana to pull data from Prometheus.

### Create Dashboards and Alerts
1. Use Grafana to create visual dashboards.
2. Configure Prometheus for alerting.

This setup helps ensure application performance and reliability through comprehensive monitoring and visualization.

[Architecture](https://github.com/MuhammedNizar/Cloud_Based_System_Monitoring/assets/95206356/d0d39203-8e5c-4df5-9b22-9d28d618e5af)
