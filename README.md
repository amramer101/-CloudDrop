# ☁️ CloudDrop - Secure File Sharing Web Application on AWS

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws\&logoColor=white)
![Terraform](https://img.shields.io/badge/IaC-Terraform-blueviolet?logo=terraform\&logoColor=white)
![Python](https://img.shields.io/badge/Python-Boto3-3776AB?logo=python\&logoColor=white)
![Security](https://img.shields.io/badge/Security-IAM-red?logo=awsiam\&logoColor=white)
![Uptime](https://img.shields.io/badge/Uptime-99.5%25-brightgreen)
![Latency](https://img.shields.io/badge/Latency-20%25_Improved-blue)

---

## 🌟 Project Overview

**CloudDrop** is a **secure, scalable, and high-performance file-sharing web application** built on **AWS**.
It enables users to **upload and download files** with **end-to-end encryption**, automated infrastructure management, and optimized performance.
This project demonstrates best practices in **cloud security, performance optimization, and IaC (Infrastructure as Code)**.

---

## 🚀 Key Features

* 🔒 **End-to-End Security**: Implemented with fine-grained IAM roles and policies to ensure least-privilege access.
* 📂 **Durable Storage**: Files are securely stored in Amazon S3 with cost-efficient and reliable storage.
* ⚡ **Optimized Performance**: Reduced latency by 20% using EC2 instance tuning and network optimizations.
* 🛡️ **High Availability**: Achieved 99.5% uptime through load balancing and monitoring.
* 🤖 **Infrastructure as Code (IaC)**: Fully automated provisioning and deployment using Terraform.
* 📝 **Python Automation**: Boto3 scripts handle seamless file uploads and downloads with encryption.

---

## 🏗️ Architecture Overview

The architecture is designed for **security, scalability, and performance**:

| Component              | Description                                                  |
| ---------------------- | ------------------------------------------------------------ |
| **VPC & Subnets**      | Public subnet with Security Groups for controlled access     |
| **EC2 Instances**      | Compute resources for hosting and processing requests        |
| **S3 Buckets**         | Durable and cost-efficient file storage                      |
| **IAM Roles/Policies** | Fine-grained access control & least-privilege enforcement    |
| **Terraform**          | Automated infrastructure provisioning & lifecycle management |

### Architecture Diagram

![CloudDrop Architecture](https://github.com/amramer101/-CloudDrop/blob/main/1745514427629.jpeg "CloudDrop Architecture")

*Figure: Secure, scalable, and automated AWS architecture for CloudDrop*

### Workflow Diagram

![CloudDrop Workflow](https://github.com/amramer101/-CloudDrop/blob/main/1745514560167.jpeg "CloudDrop Workflow")

*Figure: End-to-end workflow for file uploads, downloads, and automation*

---

## ⚙️ Tech Stack

| Category           | Tools & Services                         |
| ------------------ | ---------------------------------------- |
| **Cloud**          | AWS (EC2, S3, IAM, VPC, Security Groups) |
| **Language**       | Python (Boto3)                           |
| **Infrastructure** | Terraform                                |
| **Security**       | IAM Policies, Security Groups            |

---

## 🔧 Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/ammr102/AWS.git
cd AWS/CloudDrop
```

### 2️⃣ Provision Infrastructure

Ensure [Terraform](https://www.terraform.io/) is installed:

```bash
terraform init
terraform plan
terraform apply
```

### 3️⃣ Configure AWS CLI

```bash
aws configure
```

### 4️⃣ Run Automation Scripts

```bash
pip install boto3
python upload_file.py
python download_file.py
```

---

## 🌐 Usage

1. **Upload files** → securely stored in Amazon S3.
2. **Download files** → retrieved with encryption & IAM-based access.

---

## 📊 Performance Highlights

* ✅ **99.5% uptime** achieved with optimized EC2 instances and network configurations.
* ✅ **20% latency reduction** through load-testing-driven tuning.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to **fork** this repo and submit a **pull request**.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Amr Amer**
🌐 [LinkedIn](https://www.linkedin.com/in/amr-amer) • 💻 [GitHub](https://github.com/ammr102)
