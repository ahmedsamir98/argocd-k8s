# ArgoCD and Kubernetes Configurations

Welcome to the ArgoCD and Kubernetes Configurations repository! This repository contains configurations and best practices for deploying and managing Kubernetes applications using ArgoCD. It is designed to support large-scale and complex environments with multiple services across various environments (e.g., production, staging).

environments/: Contains environment-specific configurations (e.g., production, staging). Each folder has an apps.yaml file to define the applications deployed in the respective environment.
applications/: Contains application-specific configurations. These configurations leverage Kustomize to define Kubernetes resources.
clusters/: Contains cluster-specific configurations, such as cluster-wide policies or resource quotas.
docs/: Additional documentation and best practices.

To understand the deployment process and how this repository is structured for large-scale environments, please read the detailed explanation on Medium:
https://medium.com/@aahmedsamir98/managing-large-complex-environments-with-argocd-managing-multi-environment-configurations-with-545d89b7730e.


Happy deploying with ArgoCD! 🚀
