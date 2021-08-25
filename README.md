# - RaspberryPI on K3S worker node

+ ## Prometheus Installtion(with Grafana)
```
kubectl create -f promethues/prometheus/
kubectl create -f promethues/node-exporter/
kubectl create -f promethues/kube-state-metrics-configs/
kubectl create -f promethues/grafana/

```

### Prometheus_PORT: 30000, Grafana_PORT: 30001
