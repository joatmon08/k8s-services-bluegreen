# Service Mesh Examples for Blue/Green Deployment on Kubernetes

These are example route configurations for doing a blue/green deployment of an application on Kubernetes.

## How They Work
* Each configuration references the [joatmon08/turquoise](https://github.com/joatmon08/turquoise) application.
* There is a "blue" version of the service and a "green" version of the service.
* Each route configuration denotes the stage of blue/green.

## Service Meshes
* Istio 0.2.12
* Linkerd 1.3.2

## Dependencies
* Kubernetes 1.8