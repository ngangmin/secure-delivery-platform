# Secure Delivery Platform

A small FastAPI service with a hardened container image and a CI pipeline, built as a DevSecOps practice project.

## Run it
    docker build -t secure-app:dev .
    docker run --rm -p 8000:8000 secure-app:dev
    curl localhost:8000/healthz

## What it demonstrates
- Non-root, minimal container image
- Automated lint, test and build with GitHub Actions
- Least-privilege workflow permissions

Next phases: security scanning, Terraform, GitOps, policy enforcement, observability.
