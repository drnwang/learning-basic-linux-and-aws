# Getting Started with Linux and AWS for Beginners

Welcome to this beginner-friendly guide on learning Linux and AWS. This repository is built from training material and designed for people with **no prior IT experience**. Each folder covers a topic using simple explanations, real-world analogies, mini-quizzes, diagrams, and hands-on examples.

It now includes projects and walkthroughs aligned with **AWS Certified Cloud Practitioner** and **AWS Solutions Architect - Associate** certification objectives.

---

## 🛍️ Who is this for?
- **Beginners** who want to start learning Linux and AWS tools
- **Job seekers** pursuing cloud, DevOps, or IT support roles
- **Students** or career changers exploring infrastructure
- **AWS certification candidates** preparing for Cloud Practitioner or Associate-level exams

## 💡 What will you learn?
You'll learn how to:
- Use Linux commands to navigate and manage a system
- Launch and connect to AWS virtual machines (EC2)
- Secure cloud servers and transfer files
- Manage users, install software, and more
- Configure IAM users, policies, and permissions
- Host a static website on S3
- Launch and harden EC2 instances with SSH and Security Groups
- Set budgets and track AWS Free Tier usage
- Understand VPC, subnets, routing, and network isolation
- Use Terraform and JSON IAM policies
- Leverage AWS Management Tools like Systems Manager, CloudWatch, and CloudTrail to automate, monitor, and secure workloads
- Work with Docker containers and images for isolated, portable applications
- Use Git and GitHub for source control, collaboration, and version history
- Write simple Python scripts to automate tasks and interact with cloud APIs
- Query cloud databases using SQL fundamentals (SELECT, JOIN, WHERE, etc.)
- Deploy and scale applications using **Elastic Load Balancer (ELB)** and **Auto Scaling Groups (ASG)**
- Set up **CloudWatch Alarms** for EC2 health and metrics
- Design highly available architectures with **multi-AZ deployments**
- Use **EFS** for scalable, shared file storage between EC2s

## ⏱️ When should you use this?
- While preparing for AWS Certified Cloud Practitioner (CCP) or Solutions Architect – Associate exams
- During technical interviews that involve Linux or AWS CLI
- As reference during IT training or bootcamps

## 🌍 Where does this apply?
- **Linux-based systems** (Ubuntu, Amazon Linux, etc.)
- **AWS Cloud platform** — especially EC2, S3, IAM, RDS, VPC, and CLI

## ❓ Why Linux and AWS?
- Linux powers most cloud servers and devices
- AWS is the most widely used cloud provider
- Both are foundational to modern IT and cloud careers

## 🔧 How to Use This Repository
1. **Download or clone the repo**
2. Pick a folder you're interested in (start with [`1_basic-linux-commands/`](./1_basic-linux-commands/))
3. Open the `.sh` script or `.md` guide inside
4. Read the comments and run the examples in your terminal or AWS CloudShell

Each script is explained line-by-line with real-life comparisons. Every subfolder also includes a `README.md` with beginner-friendly lessons, examples, analogies, quizzes, checklists, troubleshooting tips, and a visual diagram.

---

## 📂 Folder Overview

| Folder                               | What it Covers                                      | Includes                        |
|--------------------------------------|-----------------------------------------------------|----------------------------------|
| [`basic-commands`](../linux-fundamentals/01_basic-commands/)            | Navigate the Linux system like a file cabinet       | ✅ Quiz, Diagram, Exercise, Checklist |
| [`file-permissions`](../linux-fundamentals/02_file-permissions/)                | Control access to files like door locks             | ✅ Quiz, Diagram, Exercise, Checklist |
| [`user-group-management`](../linux-fundamentals/03_user-group-management/)       | Manage users like team members in an office         | ✅ Quiz, Diagram, Exercise, Checklist |
| [`file-searching`](../linux-fundamentals/04_file-searching/)    | Find and compress files like digital organizers     | ✅ Quiz, Diagram, Exercise, Checklist |
| [`software-management`](../linux-fundamentals/05_software-management/)             | Install tools like apps on your phone               | ✅ Quiz, Diagram, Exercise, Checklist |
| [`networking`](../linux-fundamentals/06_networking/)                      | Check connections like testing WiFi or pinging sites| ✅ Quiz, Diagram, Exercise, Checklist |
| [`ec2-setup`](../aws-fundamentals/02_ec2-setup/)                         | Launch virtual machines in the cloud                | ✅ Quiz, Diagram, Exercise, Checklist |
| [`iam-policies`](../aws-fundamentals/03_iam-policies/)              | Create users, roles, and manage permissions         | ✅ Quiz, Diagram, Exercise, Checklist |
| [`vpc-basics`](../aws-fundamentals/01_vpc-basics/)                  | Understand subnets, gateways, and routing tables    | ✅ Quiz, Diagram, Exercise, Checklist |
| [`terraform`](../devops-tools/01_terraform/) | Automate infrastructure with Terraform              | ✅ Quiz, Diagram, Exercise, Checklist |
| [`docker`](../devops-tools/03_docker/)           | Containerize apps for portability and isolation     | ✅ Quiz, Diagram, Exercise, Checklist |
| [`git-github`](../devops-tools/02_git-github/)                 | Track code history and collaborate in the cloud     | ✅ Quiz, Diagram, Exercise, Checklist |
| [`python`](../devops-tools/04_python/)                         | Automate tasks and write cloud scripts              | ✅ Quiz, Diagram, Exercise, Checklist |
| [`sql`](../devops-tools/05_sql/)                 | Query cloud databases using standard SQL            | ✅ Quiz, Diagram, Exercise, Checklist |
| [`cloudwatch`](../aws-fundamentals/04_cloudwatch/)   | Monitor systems with alarms and health checks       | ✅ Quiz, Diagram, Exercise, Checklist |
| [`s3-storage`](../aws-fundamentals/06_s3-storage/)                   | Share file systems across multiple EC2 instances    | ✅ Quiz, Diagram, Exercise, Checklist |
| [`elb-autoscaling`](../aws-fundamentals/05_elb-autoscaling/)       | Add load balancing and auto-scaling to EC2 apps     | ✅ Quiz, Diagram, Exercise, Checklist |

---

## 🧪 Capstone Projects (Recommended for Exam Prep)

| Project | AWS Services Involved | Skills Practiced |
|---------|------------------------|------------------|
| Host a Static Website on S3 | S3, IAM | Public access, buckets, policies |
| Launch EC2 with NGINX & SSH | EC2, VPC, Key Pairs | Instance setup, security groups, bootstrap scripts |
| IAM User & Policy Simulation | IAM | Least privilege, custom policies, MFA |
| Budget and Free Tier Monitor | Budgets, Cost Explorer | Alerting, pricing models, billing dashboard |
| RDS Instance with EC2 Integration | RDS, EC2, Security Groups | Database setup, connection security |
| Build a VPC with 2-tier architecture | VPC, Subnets, EC2, RDS | Network isolation, routing, architecture design |
| Automate EC2 + S3 with Terraform | EC2, S3, Terraform CLI | Infrastructure-as-code practice |
| Patch EC2 with Systems Manager & Monitor Logs | SSM, CloudWatch | EC2 management, automation, log collection |
| Auto-Scale a Web App with ELB + ASG | EC2, ASG, ELB, CloudWatch Alarms | Elastic load balancing, high availability, alerts |
| Shared Storage Across EC2 Using EFS | EC2, EFS, Security Groups | Shared volumes, scalable file systems |

Each project includes checklists and diagrams, and is mapped to AWS exam objectives.

---

Let us know if you'd like to contribute additional labs or challenges. Stay curious, and good luck with your AWS journey!
