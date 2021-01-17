# Factorio Server

[factorio](https://github.com/coreysabia/FactorioServer) - A Helm chart for running factorio in kubernetes

```console
helm repo add coreysabia https://coreysabia.github.io/FactorioServer/
helm repo update
helm install factorio coreysabia/FactorioServer 
```

## Introduction

This chart deploys Factorio on a [Kubernetes](http://kubernetes.io) cluster using the [Helm](https://helm.sh) package manager.

## Prerequisites


## Installing the Chart

To install the chart with the release name ``:

```console
helm install factorio coreysabia/FactorioServer
```

## Releases
Releases are published using the official helm release action in github. 
https://github.com/helm/chart-releaser-action