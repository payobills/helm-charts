# payobills helm charts

Helm charts for all microservices for the [payobills](https://github.com/payobills/payobills) app.

## Notice
These charts are in alpha release and are uploaded manually for now. Until this repo is completely automated, installation can only be done with raw urls.

Example:
```
helm install -n payobills bills \
    https://github.com/payobills/helm-charts/raw/main/charts/bills/charts/bills-v0.2.0-alpha.7.tar.gz \
    --values <path-to-your-values.yaml>
```
