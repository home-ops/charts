# Pi-Hole helm chart

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo and install as follows:

```console
helm repo add home-ops https://home-ops.github.io/charts/
helm upgrade -i pihole home-ops/pihole -f values.yaml
```

