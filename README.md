# Danila Zanin

Senior DevOps engineer. I run hybrid infrastructure: bare-metal Linux and Hyper-V on-prem, AWS for public services, Kubernetes on both (Kubespray and EKS), GitOps with Argo CD and Helm. Terraform for cloud resources, Ansible for the bare-metal fleet.

## Open source

Tools I wrote for problems I kept running into.

| Project | What it does |
|---|---|
| [helm-unstick](https://github.com/DanilaZanin/helm-unstick) | Recovers a Helm release stuck with "another operation (install/upgrade/rollback) is in progress". Checks that the operation is really dead before it rolls back, and refuses when it cannot tell. Tested end to end on Helm 3 and Helm 4. |
| [ci-why](https://github.com/DanilaZanin/ci-why) | Explains which rule added or dropped a GitLab CI job, clause by clause, with the variable values it used. Its answers are compared with a real GitLab on every release. |
| [devops-starters](https://github.com/DanilaZanin/devops-starters) | Ten copy-paste starters (Ansible, Terraform, Argo CD, Vault, RabbitMQ, Redis, Kafka and others). Each one ships a test that reproduces the production trap it avoids. |
| [vault-db-access](https://github.com/DanilaZanin/vault-db-access) | Self-service portal for temporary PostgreSQL and ClickHouse credentials on top of HashiCorp Vault's database secrets engine. |

## Stack

AWS, Terraform, Ansible, Kubernetes, Helm, Argo CD, GitLab CI, GitHub Actions, HashiCorp Vault, PostgreSQL (Patroni), ClickHouse, Kafka, RabbitMQ, Redis, Prometheus, Grafana, ELK, Python, Bash.

## Contact

[LinkedIn](https://www.linkedin.com/in/danila-zanin-644208202/)
