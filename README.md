# aks-demo
Demo for azure AKS

## Prepairing
```ps
az login
az group create --name kubdemo --location eastus
az aks create -g kubdemo -n demoCluster --node-count 1 --generate-ssh-keys
az aks get-credentials -g kubdemo -n demoCluster
```
## AKS
```ps
kubectl get nodes
kubectl get pods
kubectl get pods --all-namespaces
```

