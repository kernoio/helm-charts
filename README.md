# Kerno Agent Helm Chart 

## Add the repository to your local helm:

```bash

helm repo add kerno https://kernoio.github.io/helm-charts

```

## Install the Chart

```bash

helm install kerno-agent kerno/agent \
  --create-namespace \
  --namespace kerno \
  --set api-key="<KERNO_API_KEY>"
```
