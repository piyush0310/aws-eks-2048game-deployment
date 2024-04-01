ct# Install eksctl

Please follow the prerequisites doc before this.

## create cluster using Fargate

```
eksctl create cluster --name demo-cluster --region us-east-1 --fargate
```

## Delete the cluster

```
eksctl delete cluster --name demo-cluster --region us-east-1
```


