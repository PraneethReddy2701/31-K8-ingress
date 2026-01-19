# Ingress Controller

### Create an IAM OIDC provider

```
eksctl utils associate-iam-oidc-provider \
    --region <region-code> \
    --cluster <your-cluster-name> \
    --approve
    
```

### Download an IAM policy

```
curl -o iam-policy.json https://raw.githubusercontent.com/kubernetes-sigs/aws-load-balancer-controller/v2.17.0/docs/install/iam_policy.json

```