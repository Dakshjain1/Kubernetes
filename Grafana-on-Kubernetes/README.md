# Grafana-on-Kubernetes

The link to the detailed article is =>
https://medium.com/@daksh.jain00/prometheus-grafana-on-kubernetes-85ca548d71da

Contains the Dockerfile to create a Grafana server and the manifest file for setting it up on Kubernetes.

## USAGE
```
kubectl create -k .
```
This will just call the Kustomization file and it will automatically create the rest of the files.
