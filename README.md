# Calculi users

To install the chart, run:

helm upgrade --install --debug --wait -f deploy.yaml datadog-agent -n guide-rails datadog/datadog

See the charts/deploy.yaml.template file for the representation of the deploy.yaml

# Datadog Helm Charts

[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/datadog)](https://artifacthub.io/packages/search?repo=datadog) 

Official Helm charts for Datadog products. Currently supported:
- [Datadog Agents](charts/datadog/README.md) (datadog/datadog)

## How to use Datadog Helm repository

You need to add this repository to your Helm repositories:

```
helm repo add datadog https://helm.datadoghq.com
helm repo update
```
