# MP
Installs the full system

## TL;DR;

```console
$ helm install mpw
```

## Installing the Chart

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
| `idp.enabled` | Deploy IAM/IDP service | true |
| `ssms.enabled` | Deploy SSMS server | true |
| `scp.enabled` | Deploy SCP services | true |
| `scp.scp.tracing.opencensus.collector.host` | Hostname of OC-Collector service | oc-collector |
| `tis.enabled` | Deploy TokenIssuer services | true |
| `opencensus.enabled` | Deploy OC/OpenCensus services | true |