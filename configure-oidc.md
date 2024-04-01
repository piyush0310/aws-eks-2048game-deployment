

## Check if there is an IAM OIDC OpenID Connect (OIDC) provider configured already

If not, run the below command

```
eksctl utils associate-iam-oidc-provider --cluster $cluster_name --approve
```
