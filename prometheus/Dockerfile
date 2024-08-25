# Use the official Prometheus image as a base
FROM prom/prometheus:latest

# Copy Prometheus configuration files into the container
COPY prometheus.yml /etc/prometheus/prometheus.yml

# Expose the port Prometheus will run on
EXPOSE 9090

# Set the default command to run Prometheus
CMD [ "--config.file=/etc/prometheus/prometheus.yml" ]
