# Factorio Server
This repository holds our deployment of our Factorio server. It contains the actual factorio server itself, as well as some ancillary apps that go along with it. This repo is structured as a helm chart that you can deploy to any Kubernetes cluster with internet access. 


## Installing

To install the application, run `helm install . --generate-name` after cloning this repo.