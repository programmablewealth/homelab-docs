# Portainer Virtual Machine

This server will be running Portainer and host multiple Docker applications.

- IP address: 10.0.0.14

The Portainer UI is accessible at the following link.

https://10.0.0.14:9443/

admin, portainerpassword

## List of Docker Applications Running

- Portainer
- Multiple Wordpress instances with their own mysql databases
- Node Exporter

## Monitoring

Node Exporter is running via docker compose and is exposed via http://10.0.0.14:9100 and consumed via Prometheus running on the monitoring server virtual machine
