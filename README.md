# orders-api
FastAPI service with a security-first CI pipeline: tests, container build, Trivy scan, push to GHCR, then an automated GitOps promotion PR to platform-config. CI never touches the cluster.
