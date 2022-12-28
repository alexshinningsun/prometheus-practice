# prometheus-practice
This is a practice for using helm-prometheus.

The First practice is referencing

# Helm Commands
```
# Init prometheus operator
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm repo update

# Generate all prometheus operator manifest files
helm template monitoring prometheus-community/prometheus -f ./values.yaml > ./manifest.yaml

# Show current configuration values
helm show values prometheus-community/prometheus
``` 
