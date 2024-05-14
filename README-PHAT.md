```sh
helm upgrade -f STS-deployment.yaml grafana . --install --dry-run > sts.yaml
```

```sh
helm upgrade -f STS-deployment.yaml grafana . --install
```

```sh
helm upgrade -f PVC-deployment.yaml grafana . --install --dry-run > pvc.yaml
```

```sh
helm upgrade -f PVC-deployment.yaml grafana . --install
```