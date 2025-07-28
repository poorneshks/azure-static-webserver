# 🌐 Azure Static Webserver Deployment using Terraform

This project provisions an Azure Virtual Machine and deploys a static website on it using **Terraform** and **cloud-init** automation.

---

## 🛠️ Technologies Used

- **Terraform** for Infrastructure as Code (IaC)
- **Azure Virtual Machine** (Linux-based)
- **cloud-init** for provisioning and configuration
- **NGINX** as the web server
- **GitHub** for version control

---

## 📂 Project Structure

# 🌐 Azure Static Webserver Deployment using Terraform

This project provisions an Azure Virtual Machine and deploys a static website on it using **Terraform** and **cloud-init** automation.

---

## 🛠️ Technologies Used

- **Terraform** for Infrastructure as Code (IaC)
- **Azure Virtual Machine** (Linux-based)
- **cloud-init** for provisioning and configuration
- **NGINX** as the web server
- **GitHub** for version control

---

## 📂 Project Structure


---

## 🚀 How It Works

1. **Terraform** authenticates with Azure and provisions a Linux VM.
2. VM uses **cloud-init** to:
   - Install NGINX
   - Create a sample static webpage (`index.html`)
3. Public IP is output for you to visit in the browser.

---

## 🔧 Getting Started

### Prerequisites:
- Terraform installed (`terraform -v`)
- Azure CLI installed (`az login`)
- Azure student/free subscription active

### Steps:

```bash
# 1. Initialize Terraform
terraform init

# 2. Review the plan
terraform plan

# 3. Apply the infrastructure
terraform apply

# 4. Visit the public IP in your browser
