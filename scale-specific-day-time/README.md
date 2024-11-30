# apply manifest
```bash
kubectl apply -f manifest/namespace.yaml
kubectl apply -f manifest/deployment.yaml
kubectl apply -f manifest/nginx-scaler.yaml
# or run script
./run.sh
```

# check keda
```bash
kubectl get scaledobjects -n backend-project
kubectl get pods -n backend-project -w
```


