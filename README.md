## Introduction

This chart bootstraps BigID App deployment on a [Kubernetes](http://kubernetes.io) cluster using the [Helm](https://helm.sh) package manager.

## Installing the Chart

To install the chart with the release name `myApp`:

```$ helm install myApp . --namespace [NAMESPACE]```

## Upgrding the chart

```$ helm upgrade myApp . --namespace [NAMESPACE]```

## Uninstalling the Chart

```$ helm uninstall myApp --namespace [NAMESPACE]```

## Rollback the Chart

```$ helm rollback myApp [REVISION]```

