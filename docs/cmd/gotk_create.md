## gotk create

Create or update sources and resources

### Synopsis

The create sub-commands generate sources and resources.

### Options

```
      --export              export in YAML format to stdout
  -h, --help                help for create
      --interval duration   source sync interval (default 1m0s)
```

### Options inherited from parent commands

```
      --kubeconfig string   path to the kubeconfig file (default "~/.kube/config")
      --namespace string    the namespace scope for this operation (default "gitops-system")
      --timeout duration    timeout for this operation (default 5m0s)
      --verbose             print generated objects
```

### SEE ALSO

* [gotk](gotk.md)	 - Command line utility for assembling Kubernetes CD pipelines
* [gotk create helmrelease](gotk_create_helmrelease.md)	 - Create or update a HelmRelease resource
* [gotk create kustomization](gotk_create_kustomization.md)	 - Create or update a Kustomization resource
* [gotk create source](gotk_create_source.md)	 - Create or update sources

