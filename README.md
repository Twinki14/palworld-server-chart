# palworld-server-chart

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/palworld-server-chart&style=flat-square)](https://artifacthub.io/packages/search?repo=palworld-server-chart)
[![GitHub License](https://img.shields.io/github/license/Twinki14/palworld-server-chart?style=flat-square)](https://github.com/Twinki14/palworld-server-chart/blob/main/LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/Twinki14/palworld-server-chart?style=flat-square)](https://github.com/Twinki14/palworld-server-chart/releases)
[![GitHub Downloads](https://img.shields.io/github/downloads/twinki14/palworld-server-chart/total?style=flat-square)](https://github.com/Twinki14/palworld-server-chart/releases)
[![OCI security profiles](https://img.shields.io/badge/oci%3A%2F%2F-palworld%20server%20chart-blue?logo=kubernetes&logoColor=white&style=flat-square)](https://github.com/twinki14/palworld-server-chart/packages)


Official helm chart for the popular [Palworld Server Docker](https://github.com/thijsvanloef/palworld-server-docker) docker image


## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repository as follows:

```console
helm repo add palworld-server https://twinki14.github.io/palworld-server-chart
```

Running `helm search repo palworld-server` should now display the chart and it's versions

To install the helm chart, use
```console
helm install palworld palworld-server/palworld --create-namespace --namespace palworld-server
```

## Values

You can find the `values.yaml` summary in [the charts directory](https://github.com/Twinki14/palworld-server-chart/blob/main/charts/palworld/values.yaml)
