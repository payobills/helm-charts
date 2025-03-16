# payobills helm charts

Helm charts for all microservices for the [payobills](https://github.com/payobills/payobills) app.

## getting started

Add the helm repo

```
helm repo add payobills https://payobills.github.io/helm-charts
```

### install or update a chart

```
helm upgrade --install --create-namespace -n payobills payobills/bills --generate-name --version 0.2.0-alpha.7
```

---

## dev workflow

Commands used to work on this repo.

### regenerate index file

```bash
helm repo index --merge index.yaml .
```

##