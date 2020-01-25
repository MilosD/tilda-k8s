# Worker
```
wget https://github.com/containernetworking/plugins/releases/download/v0.7.5/cni-plugins-amd64-v0.7.5.tgz
```
```
sudo tar -xzvf cni-plugins-amd64-v0.7.5.tgz --directory /opt/cni/bin/
kubectl apply -f "https://cloud.weave.works/k8s/net?k8s-version=$(kubectl version | base64 | tr -d '\n')"
kubectl get pods -n kube-system
```

