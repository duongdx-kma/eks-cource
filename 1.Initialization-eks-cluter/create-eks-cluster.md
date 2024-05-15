# Create EKS Cluster & Node Groups


## Step-01: Create EKS cluster using eksctl

```
# Create cluster:
eksctl create cluster --name=eks-demo \
                      --region=ap-southeast-1 \
                      --ap-southeast-1a,ap-southeast-1b \
                      --without-nodegroup 

# list all cluster:
eksctl get cluster
```