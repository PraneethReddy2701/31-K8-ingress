# Ingress Controller

### Create an IAM OIDC provider

```
eksctl utils associate-iam-oidc-provider \
    --region <region-code> \
    --cluster <your-cluster-name> \
    --approve
```

