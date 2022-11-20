# helm-charts

[![Release Charts](https://github.com/kiaedev/helm-charts/actions/workflows/release.yaml/badge.svg)](https://github.com/kiaedev/helm-charts/actions/workflows/release.yaml)

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```bash
helm repo add kiaedev https://kiaedev.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo kiaedev` to see the charts.

To install the kiae chart:

    helm install kiae kiaedev/kiae

To uninstall the chart:

    helm delete kiae