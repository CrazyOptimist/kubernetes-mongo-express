# K8s mongo-express deployment
You need to have `kubectl` and `minikube` installed and configured on your machine.
Run these commands in your terminal
```bash
kubectl apply -f mongo-secret.yaml
kubectl apply -f mongo-configmap.yaml
kubectl apply -f mongo.yaml
kubectl apply -f mongo-express.yaml
```
