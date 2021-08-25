+ # Prometheus Installtion(with Grafana)
```
kubectl create ns monitoring

kubectl create -f promethues/kubernetes-prometheus/
kubectl create -f promethues/kubernetes-node-exporter/
kubectl create -f promethues/kube-state-metrics-configs/
kubectl create -f promethues/kubernetes-grafana/
```

### Prometheus_PORT: 30000, Grafana_PORT: 30001
