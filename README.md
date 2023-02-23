**Nginx deployment**

```
kubectl create -f nginx.yml -f nginx-service.yml
```
To check for deployment status

```
kubectl get deployment nginx -o yaml
```
