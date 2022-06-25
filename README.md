# Helm chart repository
## Usage

[Helm](https://helm.sh) must be installed to use the chart.  
Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

To add the repo:
```shell
helm repo add bbartsch https://bbartsch.github.io/helm-charts

# Update repos
helm repo update
```

To install a chart:

```shell
helm install my-<chart-name> bbartsch/<chart-name>

# example
helm install my-example bbartsch/example
```

To uninstall the chart:
```shell
helm delete my-<chart-name>

# example
helm delete my-example
```