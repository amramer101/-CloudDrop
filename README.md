# ☁️ CloudDrop - Secure File Sharing Web Application on AWS

---

## 🌟 Project Overview

**CloudDrop** is a **secure, scalable, and high-performance file-sharing web application** built on **AWS**.
It enables users to **upload and download files** with **end-to-end encryption**, automated infrastructure management, and optimized performance.

---

## 🚀 Features

* 🔒 **End-to-End Security**: Enforced encryption with fine-grained IAM roles & policies.
* 📂 **Durable Storage**: Reliable file storage with Amazon S3.
* ⚡ **Performance Optimized**: 20% lower latency with tuned EC2 instances and network configuration.
* 🛡️ **High Availability**: Achieved 99.5% uptime.
* 🤖 **Infrastructure as Code**: Fully automated provisioning using Terraform.

---

## 🏗️ Architecture Overview

| Component              | Description                                                  |
| ---------------------- | ------------------------------------------------------------ |
| **VPC & Subnets**      | Public subnet with Security Groups for controlled access     |
| **EC2 Instances**      | Hosting and compute resources                                |
| **S3 Buckets**         | Durable and cost-efficient file storage                      |
| **IAM Roles/Policies** | Fine-grained access control & least-privilege enforcement    |
| **Terraform**          | Automated infrastructure provisioning & lifecycle management |

📌 Example Architecture Diagram: (https://github.com/amramer101/-CloudDrop/blob/main/1745514427629.jpeg "1745514427629.jpeg")\\

---

## ⚙️ Tech Stack

* **Cloud**: AWS (EC2, S3, IAM, VPC, Security Groups)
* **Language**: Python (Boto3)
* **Infrastructure**: Terraform
* **Security**: IAM Policies, Security Groups

---

## 🔧 Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/ammr102/AWS.git
cd AWS/CloudDrop
```
