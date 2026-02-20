# Helm Chart - NIM Model Deployment

This Helm Chart deploys a NIM model in your k8s cluster.

## Installation instructions

```bash
helm install nim-llm . --namespace <namespace> --create-namespace
```

Ensure it has een installed correctly
```
kubectl get pods -n <namespace>
```

Result, check "http://nim-llama.<ingress_dns>"
