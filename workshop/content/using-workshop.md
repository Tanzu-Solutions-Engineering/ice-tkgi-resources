When you log-in to the workshop portal, you will be allocated a dedicated  Kubernetes namespace in a TKGI cluster.

You can perform Kubernetes operations in this namespace.

 For example:

```execute
kubectl get ns
kubectl get pods
```

Remember that access is limited to your namespace.  For example, the below operation will give an error message:

```execute
kubectl get pods -n pks-system
```
