# Dagster Cloud Agent Helm Chart

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/dagster-cloud)](https://artifacthub.io/packages/search?repo=dagster-cloud)

## Usage

We use Helm to manage our Kubernetes application in a configurable, replicable, and sharable way. Helm can be installed by following the [Helm installation guide](https://helm.sh/docs/intro/install/).

To download and install the Dagster Cloud Agent Helm chart, use the following command:

```bash
helm repo add dagster-cloud https://dagster-io.github.io/helm-user-cloud
```

We can check the most recent version of the Dagster chart in our chart repository by searching through it:

```bash
helm search repo dagster-cloud
```

To use new releases of the Dagster Cloud Agent Helm chart, we'll need to update our chart repository cache:

```bash
helm repo update
```

## Tutorial

For a introductory guide on setting up Dagster Cloud Agent using Helm, [check out our documentation](https://docs.dagster.cloud/agents/kubernetes/setup).
