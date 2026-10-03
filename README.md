<p align="center">
  <img src="assets/banner.png" alt="Danila Zanin, Senior DevOps / SRE. Kubernetes, GitOps, Vault, tools for 3 a.m. problems" width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/danila-zanin-644208202/"><img src="https://img.shields.io/badge/LinkedIn-danila--zanin-ff6b5e?style=flat-square&labelColor=0d1017" alt="LinkedIn"></a>
</p>

Senior DevOps engineer. I run hybrid infrastructure: bare-metal Linux and Hyper-V on-prem, AWS for public services, Kubernetes on both (Kubespray and EKS), GitOps with Argo CD and Helm. Terraform for cloud resources, Ansible for the bare-metal fleet.

I also run AI coding agents every day and write about what survives production.

## Tools I wrote for problems I kept running into

<table>
<tr>
<td width="50%" valign="top">

### [helm-unstick](https://github.com/DanilaZanin/helm-unstick)
Recovers a Helm release stuck with "another operation (install/upgrade/rollback) is in progress". Checks that the operation is really dead before it rolls back, and refuses when it cannot tell. Tested end to end on Helm 3 and Helm 4.

`Go` `Helm`

</td>
<td width="50%" valign="top">

### [kubectl-whydied](https://github.com/DanilaZanin/kubectl-whydied)
kubectl plugin that explains why a container or pod died or restarted: the last termination of each container, the mechanism behind it, and the evidence with a confidence label. Checked end to end on kind with 24 failure scenarios.

`Go` `Kubernetes`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [ci-why](https://github.com/DanilaZanin/ci-why)
Explains which rule added or dropped a GitLab CI job, clause by clause, with the variable values it used. Its answers are compared with a real GitLab on every release.

`Go` `GitLab CI`

</td>
<td width="50%" valign="top">

### [vault-db-access](https://github.com/DanilaZanin/vault-db-access)
Self-service portal for temporary PostgreSQL and ClickHouse credentials on top of HashiCorp Vault's database secrets engine.

`Python` `Vault`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### [devops-starters](https://github.com/DanilaZanin/devops-starters)
Ten copy-paste starters (Ansible, Terraform, Argo CD, Vault, RabbitMQ, Redis, Kafka and others). Each one ships a test that reproduces the production trap it avoids.

`Python` `Terraform` `Ansible`

</td>
</tr>
</table>

## Stack

**Cloud and IaC**&nbsp;&nbsp; ![AWS](https://img.shields.io/badge/AWS-0d1017?style=flat-square) ![Terraform](https://img.shields.io/badge/Terraform-0d1017?style=flat-square&logo=terraform&logoColor=ff6b5e) ![Ansible](https://img.shields.io/badge/Ansible-0d1017?style=flat-square&logo=ansible&logoColor=ff6b5e)

**Kubernetes and delivery**&nbsp;&nbsp; ![Kubernetes](https://img.shields.io/badge/Kubernetes-0d1017?style=flat-square&logo=kubernetes&logoColor=ff6b5e) ![Helm](https://img.shields.io/badge/Helm-0d1017?style=flat-square&logo=helm&logoColor=ff6b5e) ![Argo CD](https://img.shields.io/badge/Argo_CD-0d1017?style=flat-square&logo=argo&logoColor=ff6b5e) ![GitLab CI](https://img.shields.io/badge/GitLab_CI-0d1017?style=flat-square&logo=gitlab&logoColor=ff6b5e) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0d1017?style=flat-square&logo=githubactions&logoColor=ff6b5e)

**Data and secrets**&nbsp;&nbsp; ![Vault](https://img.shields.io/badge/Vault-0d1017?style=flat-square&logo=vault&logoColor=ff6b5e) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL_(Patroni)-0d1017?style=flat-square&logo=postgresql&logoColor=ff6b5e) ![ClickHouse](https://img.shields.io/badge/ClickHouse-0d1017?style=flat-square&logo=clickhouse&logoColor=ff6b5e) ![Kafka](https://img.shields.io/badge/Kafka-0d1017?style=flat-square&logo=apachekafka&logoColor=ff6b5e) ![RabbitMQ](https://img.shields.io/badge/RabbitMQ-0d1017?style=flat-square&logo=rabbitmq&logoColor=ff6b5e) ![Redis](https://img.shields.io/badge/Redis-0d1017?style=flat-square&logo=redis&logoColor=ff6b5e)

**Observability and code**&nbsp;&nbsp; ![Prometheus](https://img.shields.io/badge/Prometheus-0d1017?style=flat-square&logo=prometheus&logoColor=ff6b5e) ![Grafana](https://img.shields.io/badge/Grafana-0d1017?style=flat-square&logo=grafana&logoColor=ff6b5e) ![ELK](https://img.shields.io/badge/ELK-0d1017?style=flat-square&logo=elasticstack&logoColor=ff6b5e) ![Python](https://img.shields.io/badge/Python-0d1017?style=flat-square&logo=python&logoColor=ff6b5e) ![Bash](https://img.shields.io/badge/Bash-0d1017?style=flat-square&logo=gnubash&logoColor=ff6b5e)
