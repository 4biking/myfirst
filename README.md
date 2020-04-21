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
| `indp.enabled` | Deploy IAM/IDP service | true |
| `sms.enabled` | Deploy SSMS server | true |
| `scap.enabled` | Deploy SCP services [MY|DO|INT] | true |
| `scap.scap.tracing.opencensus.collector.host` | Hostname of OC-Collector service | oc-collector |
| `tokis.enabled` | Deploy TokenIssuer services | true |
| `opencensus.enabled` | Deploy OC/OpenCensus services | true |
