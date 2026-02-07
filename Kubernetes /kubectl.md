### Quick Reference - kubectl

https://kubernetes.io/docs/reference/kubectl/quick-reference/

```
kubectl get pods o -wide
```

```
kubectl get services


kubectl get rs # replikasets
```
### Create Resources
```

kubectl apply -f ./my-manifest.yaml                 # create resource(s)
kubectl apply -f ./my1.yaml -f ./my2.yaml           # create from multiple files
kubectl apply -f ./dir                              # create resource(s) in all manifest files in dir
kubectl apply -f https://example.com/manifest.yaml  # create resource(s) from url (Note: this is an example domain and does not contain a valid manifest)
kubectl create deployment nginx --image=nginx       # start a single instance of nginx

```
