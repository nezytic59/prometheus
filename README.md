+ # Prometheus Installtion(with Grafana)
```
kubectl create -f prometheus/prometheus/
kubectl create -f prometheus/node-exporter/
kubectl create -f prometheus/kube-state-metrics-configs/
kubectl create -f prometheus/grafana/
```

### Prometheus_PORT: 30000, Grafana_PORT: 30001
