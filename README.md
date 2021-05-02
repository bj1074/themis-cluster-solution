# Prometheus monitoring app

A brief description of the project.

## Category: 

Metrics monitoring

## Deployment Method in RANCHER: 

Give Cluster Name in values yaml 
## Example:
evaluation_interval: 10s
scrape_interval: 10s
scrape_timeout: 10s
clusterInfo: yourclusterdetails


## Helm Chart installation

```
helm install metrics-monitoring-<version>.tgz --generate-name --set clusterInfo=<your clustername>
```

