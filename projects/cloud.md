# ☁️ Cloud Services Projects

[← Back to Home](../)

---

## Azure + Terraform IaC Deployment

**Course:** Cloud Services | **Status:** ✅ Complete

Deployed a full Azure VM stack using Terraform as Infrastructure as Code (IaC).

### What I did

- Wrote Terraform configuration files to provision Azure resources
- Deployed a Linux VM with networking, storage, and security groups
- Managed state files and resolved provider/quota issues
- Learned about **secret management** after accidentally exposing a subscription ID *(always use `.env` files and `.gitignore`!)*

### Screenshot

> 📸 *Add your screenshot here*

---

## Docker + Azure Container Registry

**Course:** Cloud Services | **Status:** ✅ Complete

Containerized an application and pushed it to Azure Container Registry (ACR).

### What I did

- Built a Docker image locally
- Tagged and pushed to ACR
- Verified deployment and tested the running container

### Key commands used

```bash
# Build the Docker image
docker build -t myapp .

# Tag for Azure Container Registry
docker tag myapp myregistry.azurecr.io/myapp:latest

# Push to ACR
docker push myregistry.azurecr.io/myapp:latest
```

### Screenshot

> 📸 *Add your screenshot here*

---

## MQTT over TLS on Azure Ubuntu VM

**Course:** Cloud Services | **Status:** ✅ Complete

Set up a secure MQTT broker on an Azure Ubuntu VM, managed via Terraform.

### What I did

- Provisioned an Ubuntu VM with Terraform
- Installed and configured Mosquitto MQTT broker
- Configured TLS certificates for secure communication
- Tested publish/subscribe over encrypted connection

### Screenshot

> 📸 *Add your screenshot here*

---

## Azure AI Vision Services

**Course:** Cloud Services | **Status:** ✅ Complete

Python scripting assignment using Azure Cognitive Services / AI Vision API.

### What I did

- Called Azure AI Vision REST API from Python
- Analysed images and extracted metadata
- Handled API keys securely using environment variables

### Screenshot

> 📸 *Add your screenshot here*

---

*More projects will be added as the course progresses.*