# Helm charts for [pgrwl](https://github.com/pgrwl/pgrwl)

## Usage

```bash
helm repo add pgrwl https://pgrwl.github.io/charts
helm repo update
helm search repo pgrwl
```

## Installing the Chart

To install the chart with the release name `pgrwl`:

```bash
helm upgrade pgrwl pgrwl/pgrwl --namespace=pgrwl --install --debug --atomic --wait --timeout=10m
```
