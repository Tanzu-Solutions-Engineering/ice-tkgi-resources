When you log-in to the workshop portal, you will get access to a Kubernetes namespace in a TKGI cluster.

You can perform any Kubernetes operation in this namespace.

 For example:

```execute
kubectl get ns
kubectl get pods
```

Remember that access is limited to your namespace.  For example, the below operation will give an error message:

```execute
kubectl get pods -n pks-system
```