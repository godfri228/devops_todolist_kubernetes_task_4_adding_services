## Service Deployment
```bash
kubectl apply -f .infrastructure/k8s/service.yml
```

## Access the Service
```bash
kubectl port-forward svc/todoapp-service 8080:80 -n todoapp
```
Then open http://localhost:8080
