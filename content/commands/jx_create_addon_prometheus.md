---
date: 2019-05-20T17:07:33Z
title: "jx create addon prometheus"
slug: jx_create_addon_prometheus
url: /commands/jx_create_addon_prometheus/
---
## jx create addon prometheus

Creates a prometheus addon

### Synopsis

Creates a prometheus addon.

By default Prometheus Server is exposed via Ingress entry http://prometheus.jx.your.domain.com secured
with basic authentication. Admin username is 'admin' and default password is 'admin' (see --password flag).


```
jx create addon prometheus [flags]
```

### Options

```
      --helm-update        Should we run helm update first to ensure we use the latest version (default true)
  -h, --help               help for prometheus
  -n, --namespace string   The Namespace to install into (default "jx")
      --password string    Admin password to access Prometheus web UI. (default "admin")
  -r, --release string     The chart release name (default "prometheus")
  -s, --set string         The chart set values (can specify multiple or separate values with commas: key1=val1,key2=val2)
```

### Options inherited from parent commands

```
  -b, --batch-mode                Runs in batch mode without prompting for user input (default true)
      --install-dependencies      Enables automatic dependencies installation when required
      --log-level string          Sets the logging level (panic, fatal, error, warning, info, debug) (default "info")
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx create addon](/commands/jx_create_addon/)	 - Creates an addon

###### Auto generated by spf13/cobra on 20-May-2019