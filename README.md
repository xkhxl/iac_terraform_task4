# Infrastructure as Code (IaC) with Terraform

## Objective
Provision a local Docker container using Terraform.

## Tools
- Terraform
- Docker

---

## Files
- **main.tf**: Terraform configuration to:
  - Pull the `nginx:latest` Docker image
  - Create a Docker container `nginx_container` exposing port `8081` locally

---

Go to `http://localhost:8081` to view static NGINX webpage.

---
## Screenshots

**Terraform Init**  
  ![Terraform Init](./screenshots/terraform-init.png)

**Terraform Plan**  
  ![Terraform Plan](./screenshots/terraform-plan.png)

**Terraform Apply**  
  ![Terraform Apply](./screenshots/terraform-apply.png)

**Docker Container Running**  
  ![Docker ps](./screenshots/docker-ps.png)

**Nginx Welcome Page**  
  ![Nginx Welcome](./screenshots/output.png)