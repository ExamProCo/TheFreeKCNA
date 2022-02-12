## Commands

```
minikube start --listen-address='0.0.0.0'
kubectl get pods -A
kubectl apply -f k8s/deployment.yml
curl localhost:4567
kubectl port-forward deployment/sinatra 8080:4567 --address 0.0.0.0
minikube dashboard --url
```

## Resources

https://www.honeybadger.io/blog/rails-on-kubernetes/