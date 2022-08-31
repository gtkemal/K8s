# NGINX Ingress Controller on Bear Metal
## How to install Ingress Controller

- Deploy application.
- Deploy service.
- Deploy ingress-controller.
- Create Ingress Object for Application
- Deploy Cert-Manager


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
## 4.Create Ingress Object for Application

```sh
kubectl apply -f app-ingress.yml

```
## 5.  Deploy Cert-Manager
```sh

kubectl apply -f https://github.com/cert-manager/cert-manager/releases/download/v1.9.1/cert-manager.yaml
kubectl apply -f issuer.yml

```
