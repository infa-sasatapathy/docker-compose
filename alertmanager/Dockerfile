FROM prom/alertmanager:latest

# Copy the Alertmanager configuration file into the container
COPY alertmanager.yml /etc/alertmanager/alertmanager.yml

# Expose the port Alertmanager will run on
EXPOSE 9093

# Set the default command to run Alertmanager
CMD [ "--config.file=/etc/alertmanager/alertmanager.yml" ]
