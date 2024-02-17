# payobills helm charts

Helm charts for all microservices for the [payobills](https://github.com/payobills/payobills) app.

## getting started

Add the helm repo
```
helm repo add payobills https://payobills.github.io/helm-charts
```

## install a chart

```
helm install --create-namespace -n payobills payobills/bills --generate-name --version 0.2.0-alpha.7
```
