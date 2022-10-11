## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:
```sh
  helm repo add ubikk https://ubikk.github.io/kub-training
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
ubikk` to see the charts.

To install the webserver chart:

    helm install my-webserver ubikk/training

To uninstall the chart:

    helm delete my-webserver