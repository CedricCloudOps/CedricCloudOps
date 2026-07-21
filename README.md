<h1 align="center">Cedric Severin DJIGUIMDE</h1>

<p align="center">
  <b>Infrastructure &amp; Operations Engineer</b><br>
  <i>I deploy, secure, monitor and document systems that run in production.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Linux%20%7C%20Containers%20%7C%20Automation-1A7AD7">
  <img src="https://img.shields.io/badge/Certified-AZ--104%20%7C%20CCNA-2ea44f">
  <img src="https://img.shields.io/badge/Languages-French%20(native)%20%7C%20English%20(B2)-blueviolet">
</p>

---

### About

Systems and operations engineer. I build platforms that keep running: containerized
services behind a reverse proxy, watched through metrics, logs and alerts, deployed
by CI/CD — and **documented so that someone else can operate them at 3 a.m.**

Most of my time goes to **Linux**, **Docker** and **Kubernetes**, with
**PostgreSQL**, **Redis** and **Nginx** underneath, **Prometheus / Grafana / Loki**
on top, and **Ansible**, **Terraform** and **GitHub Actions** to make it all
reproducible. I like the unglamorous parts: backups that restore, runbooks that
are actually used, and incidents that get written up afterwards.

### Tech stack

![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?logo=ansible&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white)

### Projects

| Project | What it demonstrates |
|---------|----------------------|
| ⚙️ **[ops-platform-lab](https://github.com/CedricCloudOps/ops-platform-lab)** | A full operations platform. A Flask service behind **Nginx (TLS)**, backed by **PostgreSQL**, **Redis**, **MinIO** and **Kafka**, where every upload is **scanned for viruses by a ClamAV worker** through an event-driven pipeline. Complete observability (**Prometheus, Grafana, Loki, Alertmanager**), **Kubernetes** manifests, **Terraform** + **Ansible**, and a CI that builds and **scans the image with Trivy**. |
| 🔗 **[linkr](https://github.com/CedricCloudOps/linkr)** | URL shortener with click analytics — **FastAPI**, **PostgreSQL** (Alembic migrations), **Redis**, Docker, **Kubernetes** manifests, **Terraform (AWS)**, CI/CD with security scanning and an observability stack. |
| 🔒 **[linux-hardening-ansible](https://github.com/CedricCloudOps/linux-hardening-ansible)** | Idempotent **Ansible** role that hardens Debian/Ubuntu servers: SSH lockdown, **UFW** firewall, **fail2ban**, unattended security updates and sysctl hardening. |

### What I care about

- **Restore service first, understand later** — then write the incident report.
- **A backup you have never restored is not a backup.**
- **If it is not documented, it does not exist.**

### Reach me

[![Email](https://img.shields.io/badge/Email-cedricdjiguimde%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:cedricdjiguimde@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-CedricCloudOps-181717?logo=github)](https://github.com/CedricCloudOps)

---

<p align="center"><i>« Build it reproducible. Secure it by default. Document it for the next person. »</i></p>
