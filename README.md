# Helm chart for ECK

This is a tentative to simplify the deployment of [ECK](https://www.elastic.co/guide/en/cloud-on-k8s/current/index.html)

## Requirements

As described [here](https://www.elastic.co/guide/en/cloud-on-k8s/current/k8s-deploy-eck.html), ECK's custom resource definitions have to be installed in the cluster first :

```bash
kubectl apply -f https://download.elastic.co/downloads/eck/1.3.0/all-in-one.yaml
```

## Helm install

```bash
helm install --namespace whatever eck chart
```
