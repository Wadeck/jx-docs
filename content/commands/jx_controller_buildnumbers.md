---
date: 2019-05-20T17:07:33Z
title: "jx controller buildnumbers"
slug: jx_controller_buildnumbers
url: /commands/jx_controller_buildnumbers/
---
## jx controller buildnumbers

Runs the service to generate build numbers.

### Synopsis

Runs the build number controller that serves sequential build numbers over an HTTP interface.

```
jx controller buildnumbers [flags]
```

### Examples

```
  jx buildnumbers
```

### Options

```
      --bind string   The interface address to bind to (by default, will listen on all interfaces/addresses).
  -h, --help          help for buildnumbers
      --port int      The TCP port to listen on. (default 8080)
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

* [jx controller](/commands/jx_controller/)	 - Runs a controller

###### Auto generated by spf13/cobra on 20-May-2019