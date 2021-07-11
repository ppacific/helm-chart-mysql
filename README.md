# Helm Charts
A [Helm](https://helm.sh/) repositorie with MySQL charts to be installed on [Kubernetes](https://kubernetes.io/)

## Add Helm repository

To install the repo just run:

```
helm repo add ppacific https://ppacific.github.io/helm-chart-mysql/
helm repo update
```

## Helm Charts

* [MySQL](https://ppacific.github.io/helm-chart-mysql/)

```
helm install my-release ppacific/mysql
```
