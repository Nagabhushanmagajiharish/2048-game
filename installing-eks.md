# Install EKS

Please follow the prerequisites doc before this.

## Install using Fargate

```
eksctl create cluster --name 2048-demployment --region eu-west-2 --fargate
```

## Delete the cluster

```
eksctl delete cluster --name 2048-demployment --region eu-west-2
```



