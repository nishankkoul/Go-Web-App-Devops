# Install EKS

Please follow the prerequisites doc before this.

## Install an EKS cluster with EKSCTL

```
eksctl create cluster --name go-web-app-cluster --region us-east-1 --nodegroup-name standard-workers --node-type t2.micro --nodes 2 --nodes-min 2 --nodes-max 2 --managed 
```
