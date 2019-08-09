## helm inspect

Inspect a chart

### Synopsis


This command inspects a chart and displays information. It takes a chart reference
('stable/drupal'), a full path to a directory or packaged chart, or a URL.

Inspect prints the contents of the Chart.yaml file and the values.yaml file.


```
helm inspect [CHART] [flags]
```

### Options

```
      --ca-file string     Chart repository url where to locate the requested chart
      --cert-file string   Verify certificates of HTTPS-enabled servers using this CA bundle
      --devel              Use development versions, too. Equivalent to version '>0.0.0-0'. If --version is set, this is ignored.
  -h, --help               help for inspect
      --key-file string    Identify HTTPS client using this SSL key file
      --keyring string     Path to the keyring containing public verification keys (default "~/.gnupg/pubring.gpg")
      --password string    Chart repository password where to locate the requested chart
      --repo string        Chart repository url where to locate the requested chart
      --username string    Chart repository username where to locate the requested chart
      --verify             Verify the provenance data for this chart
      --version string     Version of the chart. By default, the newest chart is shown
```

### Options inherited from parent commands

```
      --debug                           Enable verbose output
      --home string                     Location of your Helm config. Overrides $HELM-HOME (default "~/.helm")
      --host string                     Address of Tiller. Overrides $HELM-HOST
      --kube-context string             Name of the kubeconfig context to use
      --kubeconfig string               Absolute path of the kubeconfig file to be used
      --tiller-connection-timeout int   The duration (in seconds) Helm will wait to establish a connection to Tiller (default 300)
      --tiller-namespace string         Namespace of Tiller (default "kube-system")
```

### SEE ALSO

* [helm](../../docs/helm/#helm)	 - The Helm package manager for Kubernetes.
* [helm inspect chart](../../docs/helm/#helm-inspect-chart)	 - shows inspect chart
* [helm inspect readme](../../docs/helm/#helm-inspect-readme)	 - shows inspect readme
* [helm inspect values](../../docs/helm/#helm-inspect-values)	 - shows inspect values

###### Auto generated by spf13/cobra on 16-May-2019