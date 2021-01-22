# Factorio Server
This repository holds our deployment of our Factorio server. It contains the actual factorio server itself, as well as some ancillary apps that go along with it. This repo is structured as a helm chart that you can deploy to any Kubernetes cluster with internet access. 


## Installing

First make sure you have the helm client installed and that there is a valid kubeconfig available for `kubectl`. To install, first change to the `Factorio` directory and run
`helm dependency up` or `helm dep up`, followed by `helm install NAME . --values.yaml`, where NAME is the name you chose.

