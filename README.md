# Axanth Infra

Kubernetes manifests and CI/CD to deploy our web infrastructure..

## Structure

- `base/`: Reusable app components (deployment, service, ingress)
- `environments/`: Dev/prod separation using Kustomize
- `.github/`: GitHub Actions workflow for auto-deployy

## Usage

```bash
kubectl apply -k environments/prod
```
