# nodelimit-k8s


```bash
kubectl get nodes
```

```bash
kubectl describe node node01
```

```bash
kubectl cordon controlplane
```

```bash
ssh node01
systemctl status kubelet
Add 'maxPods' field if not available
save the config file.
systemctl restart kubelet
exit
```

```bash
kubectl create deployment myapp --image=nginx --replicas=5
```

```bash
kubectl scale deployment myapp --replicas=10
```
