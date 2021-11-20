# Configuring Arangodb on Kubernetes cluster.

This repository we are going to understand how we can easly setup arangodb as Loadbalancer service in kubernetes service.

## Follow below mention steps for setup arangodb.

1. Install required CRD's
   ```
       kubectl apply -f https://raw.githubusercontent.com/arangodb/kube-arangodb/1.2.1/manifests/arango-crd.yaml
       kubectl apply -f https://raw.githubusercontent.com/arangodb/kube-arangodb/1.2.1/manifests/arango-deployment.yaml
   ```
