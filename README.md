
<div align="center">

<!-- Top Animated Teal Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=008080&height=120&section=header&text=Zero_Trace_Cloud_Chat&fontSize=32&fontColor=ffffff&animation=twinkling" width="100%" />

[![Next.js](https://img.shields.io/badge/Next.js-14%2B-000000?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/)
[![Docker](https://img.shields.io/badge/Docker-24%2B-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Terraform](https://img.shields.io/badge/Terraform-1.5%2B-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)](https://www.terraform.io/)
[![Azure](https://img.shields.io/badge/Microsoft_Azure-Cloud-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://azure.microsoft.com/)
[![Website](https://img.shields.io/badge/Portfolio-kerstonanto.in-008080?style=for-the-badge&logo=google-chrome&logoColor=white)](https://kerstonanto.in)

> **A minimal build by Kerston Anto Singh**  
> *Stateless, zero-persistence real-time chat application engineered for maximum privacy, containerized with Docker, and provisioned on Microsoft Azure via Terraform.*

</div>

---

## Overview

**Zero_Trace_Cloud_Chat** is an ephemeral, ultra-secure web communication tool designed around a strict zero-data-retention model. Messages are routed purely in-memory across active sessions without writing to databases, persistent logs, or secondary storage backends.

* **Ephemeral Message Pipeline**: Session data resides strictly in volatile memory and vaporizes the moment a stream or socket connection terminates.
* **High-Scalability Architecture**: Containerized deployment designed to dynamically scale horizontally under peak traffic loads.
* **Infrastructure as Code (IaC)**: Automated provisioning of Azure cloud resources using Terraform declarative configuration files.
* **Production Containerization**: Multi-stage Dockerized setup for rapid deployment, reproducible builds, and isolated cloud hosting.

---

## Architecture & Workflow


```

[ Client Interface ] ──> ( In-Memory Stream / WebSockets )
│
▼
[ Stateless App Container ] ─> ( Isolated Docker Runtime on Azure )
│
▼
[ IaC Provisioning ] ───────> ( Terraform Managed Azure Cloud Infrastructure )

```

---

## Tech Stack & Dependencies

* **Frontend / Application Framework**: Next.js, React, Tailwind CSS
* **Containerization**: Docker, Container Registry
* **Infrastructure as Code**: Terraform
* **Cloud Infrastructure**: Microsoft Azure (App Service / Azure Container Instances)
* **Real-time Pipeline**: WebSockets / Server-Sent Events (In-Memory Routing)

---

## Quickstart & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/Kerston2104/Zero_Trace_Cloud_Chat.git
cd Zero_Trace_Cloud_Chat

```

### 2. Local Container Build & Run

```bash
# Build Docker image locally
docker build -t zero-trace-cloud-chat .

# Run container on port 3000
docker run -p 3000:3000 zero-trace-cloud-chat

```

### 3. Provisioning Azure Infrastructure via Terraform

```bash
# Navigate to Terraform directory
cd terraform

# Initialize providers and plan infrastructure
terraform init
terraform plan

# Deploy infrastructure to Microsoft Azure
terraform apply

```

---

## Operating Modes

1. **Ephemeral Chat Sessions**: Create temporary rooms where messages exist exclusively during active peer presence.
2. **Zero-Trace Termination**: Closing a window or leaving a room triggers immediate garbage collection of session states.
3. **Automated Cloud Scaling**: Deployments auto-scale based on CPU/Memory thresholds configured via Azure App Service plans.

---

## Cloud Hosting & Custom Infrastructure Consulting

Need high-availability cloud deployments, automated CI/CD pipelines, or custom Infrastructure-as-Code setups? Let's engineer a scalable solution tailored to your enterprise or startup requirements.

📬 **Get in Touch for Cloud Hosting Solutions**:

* **Email / Inquiries**: Reach out directly via the portfolio contact terminal at [contact me](mailto:contact@kerstonanto.in)
* **Services Provided**: Azure Infrastructure Provisioning, Terraform Automation, Docker Containerization, & High-Scale Web Applications.

---

## Author & Contact

**Kerston Anto Singh**

* Full-Stack Web Development, DevOps & Cloud Infrastructure
* For custom cloud architectures, production container deployments, or technical inquiries, reach out directly.

🌐 **Website**: [kerstonanto.in](https://kerstonanto.in)

GitHub: [@Kerston2104](https://www.google.com/search?q=https://github.com/Kerston2104)

---
