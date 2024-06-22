Monitoring and Visualizing REST API Performance with Prometheus and Grafana on AWS

In modern web development, monitoring and visualizing application performance is essential. This guide provides a brief overview of setting up a monitoring and visualization system for a REST API using Prometheus and Grafana, deployed on AWS.

Architecture Overview


AWS EC2 Instance: Hosts Prometheus, Grafana, and REST API endpoints.

Prometheus: Pulls metrics from REST API endpoints and pushes alerts.

Grafana: Queries Prometheus for metrics data and visualizes it in dashboards.

Ballerina Endpoints: REST API endpoints for Prometheus to pull metrics from.

Steps to Set Up
Set Up AWS EC2 Instance

Launch an EC2 instance.

Install Docker and Docker Compose.
Deploy Ballerina Endpoints

Deploy REST API endpoints.

Ensure accessibility at specified URLs.

Install and Configure Prometheus

Create a prometheus.yml configuration file.

Run Prometheus using Docker.

Install and Configure Grafana

Run Grafana using Docker.

Configure Grafana to pull data from Prometheus.

Create Dashboards and Alerts

Use Grafana to create visual dashboards.

Configure Prometheus for alerting.

This setup helps ensure application performance and reliability through comprehensive monitoring and visualization.!


[Architecture](https://github.com/MuhammedNizar/Cloud_Based_System_Monitoring/assets/95206356/d0d39203-8e5c-4df5-9b22-9d28d618e5af)
