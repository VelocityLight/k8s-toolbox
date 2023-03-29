## What this Yaml does
1. create a namespace if not exists.
2. deploy pvc.
3. deploy mariadb service & deployment.
4. deploy matomo service & deployment (expose nodeport for using) .

## How to use
```
kubectl get nodes
curl <node-ip>:30780/
```
