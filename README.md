# helm-charts

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  ``` shell
    helm repo add thegang https://thegang.tech/helm-charts
  ```    

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
thegang` to see the charts.

To install the chart:

  ``` shell
    helm install <release-name> thegang/<chart-name>
  ``` 

To uninstall the chart:

  ``` shell
    helm uninstall <release-name>
  ```    
