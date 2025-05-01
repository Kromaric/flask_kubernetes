# flask_kubernetes
Ce projet montre comment conteneuriser et déployer une application Flask connectée à PostgreSQL sur un cluster Kubernetes.

## Appliquer les fichiers Kubernetes :

kubectl apply -f k8s/postgres-secret.yaml
kubectl apply -f k8s/postgres-pv.yaml
kubectl apply -f k8s/postgres-deployment.yaml
kubectl apply -f k8s/flask-deployment.yaml
etc.

## La documentation se trouve dans le pdf que vous trouverez à la racine.