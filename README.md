# DevOps Hands-On Labs

A collection of hands-on DevOps labs, exercises, and practical implementations created while strengthening my DevOps and cloud engineering skills.

## Topics

- Ansible
- Docker
- Kubernetes
- Helm
- CI/CD
- Terraform
- AWS
- Observability

Each section contains practical configurations, exercises, and notes developed throughout my learning and experimentation.

## Ansible

Current labs include:

- Ansible inventory configuration
- Package and service management
- Apache installation and configuration
- Managing web content with Ansible
- Idempotent playbook execution

### Structure

ansible/
├── inventories/
│   └── hosts.example
└── playbooks/
    └── apache-webserver.yml

## Kubernetes

Current labs include:

- Creating and managing Pods using YAML manifests
- Deploying an Nginx container
- Inspecting Pods and cluster resources
- Managing the Pod lifecycle with `kubectl`

### Structure

```text
kubernetes/
├── README.md
├── commands.md
└── nginx-pod.yaml
```

### References

- [Kubernetes Commands](https://github.com/maziqbal/devops-hands-on-labs/blob/main/k8s/commands.md)
