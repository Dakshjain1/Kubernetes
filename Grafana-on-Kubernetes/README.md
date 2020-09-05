# Grafana-on-Kubernetes
Contains the Dockerfile to create a Grafana server and the manifest file for setting it up on Kubernetes.

## USAGE
```
kubectl create -k .
```
This will just call the Kustomization file and it will automatically create the rest of the files.
