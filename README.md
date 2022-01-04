## zelic.io Helm Charts

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add zelic-io https://zelic-io.github.io/charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
zelic-io` to see the charts.

To install the brotherscanner chart:

    helm install brotherscanner zelic-io/brotherscanner

To uninstall the chart:

    helm delete brotherscanner