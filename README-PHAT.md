## Helm repo chart grafana
```sh
helm repo add grafana https://grafana.github.io/helm-charts
```
```sh
helm repo update
helm repo list
helm repo remove xxxx
```
```sh
helm search repo -l grafana/grafana
```
```sh
helm fetch grafana/grafana --version 7.3.11 --untar
```
## Statefulset ( Statefulset )
```sh
helm upgrade -f STS-deployment.yaml grafana . --install --dry-run > sts.yaml
```
```sh
helm upgrade -f STS-deployment.yaml grafana . --install
```
## PVC ( Deployment )
```sh
helm upgrade -f PVC-deployment.yaml grafana . --install --dry-run > pvc.yaml
```
```sh
helm upgrade -f PVC-deployment.yaml grafana . --install
```

## Helm list & helm delete
```sh
helm list
helm del grafana
```
## Helm Get Values
```sh
helm get values grafana -o yaml
```