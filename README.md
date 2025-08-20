# ☁️ CloudDrop - Secure File Sharing Web Application on AWS  

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws&logoColor=white)  
![Terraform](https://img.shields.io/badge/IaC-Terraform-blueviolet?logo=terraform&logoColor=white)  
![Python](https://img.shields.io/badge/Python-Boto3-3776AB?logo=python&logoColor=white)  
![Security](https://img.shields.io/badge/Security-IAM-red?logo=awsiam&logoColor=white)  

CloudDrop is a **secure and scalable file-sharing web application** built on **AWS**.  
It provides **seamless uploads & downloads**, **end-to-end encryption**, and **fully automated infrastructure** with Terraform.  

---

## 🚀 Features
- 🔒 **End-to-End Security**: Enforced encryption with fine-grained IAM roles & policies.  
- 📂 **Durable Storage**: Amazon S3 ensures reliable and cost-efficient file storage.  
- ⚡ **Optimized Performance**: 20% latency reduction through load-testing and tuning.  
- 🛡️ **High Availability**: 99.5% uptime with optimized EC2 & network configurations.  
- 🤖 **Infrastructure as Code**: Automated provisioning & teardown via Terraform.  

---

## 🏗️ Architecture Overview
- **AWS VPC** → public subnet with Security Groups.  
- **Amazon EC2** → compute and hosting.  
- **Amazon S3** → durable file storage.  
- **IAM** → least-privilege access management.  
- **Terraform** → reproducible deployments.  

📌 Example Diagram:  
![Architecture Diagram](architecture-diagram.png)  

---

## ⚙️ Tech Stack
| Category        | Tools & Services |
|-----------------|------------------|
| **Cloud**       | AWS (EC2, S3, IAM, VPC, Security Groups) |
| **Language**    | Python (Boto3) |
| **Infrastructure** | Terraform |
| **Security**    | IAM Policies, Security Groups |

---

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/ammr102/AWS.git
cd AWS/CloudDrop
