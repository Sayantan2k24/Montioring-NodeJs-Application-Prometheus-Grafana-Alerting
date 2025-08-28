# Prometheus Alert Configuration with Grafana

This project demonstrates setting up **alerts** in Prometheus based on metric thresholds 
(e.g., CPU usage > 80%) and displaying the alerts in Grafana.

## Steps

1. Start Prometheus:
   ./prometheus --config.file=prometheus.yml

2. Ensure your Node.js app metrics are being scraped.

3. Configure Alertmanager (optional, for email/slack notifications).

4. Grafana setup:
   - Add Prometheus as a data source.
   - Provision dashboard using dashboards.yaml.
   - Alerts will appear in panels when thresholds are crossed.

## Key Files
- prometheus.yml
- alert.rules.yml
- grafana-datasources.yaml
- grafana-dashboards.yaml
- dashboard.json
