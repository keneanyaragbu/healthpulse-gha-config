# HealthPulse Config Repo (GitOps)

Kubernetes manifests and ArgoCD Application definitions for the HealthPulse platform.
ArgoCD watches this repo and deploys to EKS. Image tags are updated by the
healthpulse-gha CI pipeline after build + scan + cosign signing.
