# Main
Installs the full system

## To install

```console
$ helm install mpw
```

## Installing the Chart using Helm3

To install the chart with the release name `my-release`:

```console
$ helm install my-release mpw
```

## Uninstalling the Chart

To uninstall/delete the my-release deployment:

```console
$ helm uninstall my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.

## Configuration

| Parameter                                 | Description                                   | Default                                                 |
|-------------------------------------------|-----------------------------------------------|---------------------------------------------------------|
| `indeep.enabled` | Deploy DeeP service | true |
| `sms.enabled` | Deploy SMS server | true |
| `scap.enabled` | Deploy SCaPe services [MY | DO | INT] | true |
| `scap.scape.tracing.` | Hostname of Scape service | scape.local.net |
| `tokis.enabled` | Deploy Tokis services | true |
| `opencensus.enabled` | Deploy Opencs services | true |
