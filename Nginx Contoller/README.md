# NGINX Ingress Controller
## How to install Ingress Controller

- Deploy application.
- Deploy service.
- Deploy ingress-controller.
- Create Ingress Object for Application


## 1. Deploy application
```sh
kubectl apply -f app-dep.yml
```

## 2.Deploy application service

```sh
kubectl apply -f app-service.yml
```

## 3. Deploy nginx ingress controller 
```sh
kubectl apply -f nginx-ingress-controller-deploy.yaml

```
