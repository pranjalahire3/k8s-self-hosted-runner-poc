# k8s-self-hosted-runner-poc
Kubernetes proof of concept for GitHub Actions self-hosted runners using ARC.

# Kubernetes Self-Hosted Runner POC

## Objective

Deploy and test GitHub Actions self-hosted runners as Kubernetes Pods using Actions Runner Controller (ARC).

## Scope

* Deploy ARC in a dedicated Kubernetes namespace.
* Configure a runner scale set connected to this repository.
* Execute a GitHub Actions workflow on the Kubernetes runner.
* Verify pod scheduling, workflow execution, and runner cleanup.

## Environment

* Kubernetes test cluster
* GitHub Actions
* Actions Runner Controller (ARC)
* Helm

## Current Status

ARC controller deployed successfully. Runner scale set deployment and workflow validation are pending.
