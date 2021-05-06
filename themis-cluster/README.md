# Prometheus monitoring app

A brief description of the project.

## Category: 

Metrics monitoring

## Deployment Method in RANCHER: 

Give Cluster Name in values yaml 
## Example:
clusterInfo:edgecluster <your cluster label>


## Helm Chart installation

```
helm install metrics-monitoring-<version>.tgz --generate-name --set clusterInfo=<your clustername> --set ip.cluster=<your cluster ip address> --set ip.server=<central cluster ip>
```

