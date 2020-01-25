```
kubectl apply -f https://raw.githubusercontent.com/mmumshad/kubernetes-the-hard-way/master/deployments/coredns.yaml
kubectl get pods -l k8s-app=kube-dns -n kube-system
kubectl run --generator=run-pod/v1  busybox --image=busybox:1.28 --command -- sleep 3600
kubectl get pods -l run=busybox
kubectl exec -ti busybox -- nslookup kubernetes
```

