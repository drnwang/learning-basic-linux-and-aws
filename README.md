# Getting Started with Linux and AWS for Beginners

Welcome to this beginner‑friendly guide on learning Linux **and** AWS. This repository is designed for people with **no prior IT experience**. Each module uses plain‑English explanations, real‑world analogies, mini‑quizzes, diagrams, and step‑by‑step hands‑on examples.

It now includes walkthroughs aligned with the **AWS Certified Cloud Practitioner (CCP)** and **AWS Solutions Architect – Associate (SAA‑C03)** objectives.

---

## 🛍️ Who is this for?
- **Beginners** eager to understand Linux and AWS fundamentals
- **Job‑seekers / career‑changers** targeting cloud, DevOps, or IT support roles
- **Students** wanting practical infrastructure skills
- **AWS certification candidates** preparing for CCP or SAA

## 💡 What will you learn?
- Navigate Linux file systems, manage users, and install software
- Launch and connect to EC2, secure servers, and transfer files
- Configure IAM users, roles, and policies (least‑privilege)
- Design VPCs, subnets, gateways, and route tables
- Automate builds with Terraform, Docker, Git, and GitHub
- Monitor workloads with CloudWatch & CloudTrail; patch with SSM
- Budget, price, and optimize AWS Free Tier usage
- Build resilient, highly available architectures with ELB + Auto Scaling
- Scale storage with S3 & EFS; secure data in transit and at rest

## ⏱️ When should you use this?
- While studying for *AWS CCP* or *SAA* exams
- During technical interviews requiring CLI or cloud demos
- As a reference during IT training, bootcamps, or home labs

## 🌍 Where does this apply?
- **Linux terminals** (Ubuntu, Amazon Linux, CloudShell)
- **AWS Cloud Platform** — especially EC2, S3, IAM, RDS, VPC, CLI, and management tools

## ❓ Why Linux **and** AWS?
- Linux powers the majority of cloud servers and containers
- AWS remains the most widely adopted public‑cloud provider
- Together they form the backbone of modern DevOps and cloud careers

## 🔧 How to use this repository
1. **Clone or download** the repo
2. Start with [`01_basic-linux-commands`](01_basic-linux-commands/) (or jump to any topic)
3. Open the module README and follow the examples in your terminal or AWS CloudShell
4. Tick off each checklist and quiz yourself to reinforce learning

Each module README includes:
- Beginner‑friendly explanations
- ASCII diagrams & flowcharts
- Hands‑on lab exercises
- Mini‑quizzes with answers
- Progress checklist

---

## 📂 Folder Overview

| Folder | What it Covers | Includes |
|--------|----------------|----------|
| [01_basic-linux-commands](01_basic-linux-commands/01_basic-linux-commands.md) | Navigate the Linux system like a file cabinet | ✅ Quiz · Diagram · Exercise · Checklist |
| [02_file-permissions](02_file-permissions/02_file-permissions.md) | Control access to files like door locks | ✅ Quiz · Diagram · Exercise · Checklist |
| [03_user-and-group-management](03_user-and-group-management/03_user-and-group-management.md) | Manage users like team members in an office | ✅ Quiz · Diagram · Exercise · Checklist |
| [04_file-searching-and-archiving](04_file-searching-and-archiving/) | Find & compress files like digital organizers | ✅ Quiz · Diagram · Exercise · Checklist |
| [05_software-management](05_software-management/) | Install & update packages | ✅ Quiz · Diagram · Exercise · Checklist |
| [06_networking](06_networking/) | Check connectivity (ping, curl) | ✅ Quiz · Diagram · Exercise · Checklist |
| [07_aws-cli](07_aws-cli/) | Configure and use the AWS CLI | ✅ Quiz · Diagram · Exercise · Checklist |
| [08_aws-ec2](08_aws-ec2/) | Launch and secure EC2 instances | ✅ Quiz · Diagram · Exercise · Checklist |
| [09_security-hardening](09_security-hardening/) | Harden SSH, firewalls, and logging | ✅ Quiz · Diagram · Exercise · Checklist |
| [10_iam-policies](10_iam-policies/) | Users, groups, roles, and policies | ✅ Quiz · Diagram · Exercise · Checklist |
| [11_vpc-basics](11_vpc-basics/) | Subnets, NAT, route tables, CIDR | ✅ Quiz · Diagram · Exercise · Checklist |
| [12_infrastructure-as-code](12_infrastructure-as-code/) | Terraform IaC fundamentals | ✅ Quiz · Diagram · Exercise · Checklist |
| [13_management-tools](13_management-tools/) | CloudWatch, CloudTrail, Systems Manager | ✅ Quiz · Diagram · Exercise · Checklist |
| [14_docker-basics](14_docker-basics/) | Build & run containers | ✅ Quiz · Diagram · Exercise · Checklist |
| [15_git-github](15_git-github/) | Source control & collaboration | ✅ Quiz · Diagram · Exercise · Checklist |
| [16_python](16_python/) | Automate with Python scripts | ✅ Quiz · Diagram · Exercise · Checklist |
| [17_sql-basics](17_sql-basics/) | Query data with SQL | ✅ Quiz · Diagram · Exercise · Checklist |
| [18_elb-autoscaling](18_elb-autoscaling/) | Add load balancers & auto‑scaling | ✅ Quiz · Diagram · Exercise · Checklist |
| [19_cloudwatch-alarms](19_cloudwatch-alarms/) | Create alarms & health checks | ✅ Quiz · Diagram · Exercise · Checklist |
| [20_efs-setup](20_efs-setup/) | Shared storage across EC2 | ✅ Quiz · Diagram · Exercise · Checklist |
| [21_billing-and-costs](21_billing-and-costs/) | Budgets, Free Tier, pricing tools | ✅ Cheat‑sheet · Exercise |
| [22_architecture-examples](22_architecture-examples/) | 2‑tier & 3‑tier AWS reference diagrams | ✅ Diagrams · Templates |
| [23_exam-review-checklist](23_exam-review-checklist/) | Comprehensive CCP & SAA review list | ✅ Tracker · Links |

---

## 🧪 Capstone Projects (highly recommended)

| Project | AWS Services | Skills Practiced |
|---------|--------------|------------------|
| **Host a Static Website on S3** | S3, IAM | Public buckets, policies |
| **Launch EC2 with NGINX & SSH** | EC2, VPC | Key pairs, SGs, bootstrap |
| **IAM User & Policy Simulation** | IAM | Least privilege, MFA |
| **Budget & Free Tier Monitor** | Budgets, Cost Explorer | Alerts, cost control |
| **RDS with EC2 Integration** | RDS, EC2 | DB security groups |
| **2‑Tier VPC Architecture** | VPC, ELB, RDS | Network isolation |
| **Automate EC2 + S3 with Terraform** | Terraform, EC2, S3 | IaC pipelines |
| **Patch EC2 via Systems Manager** | SSM, CloudWatch | Automation, logging |
| **Auto‑Scale Web App with ELB + ASG** | ELB, ASG | High availability |
| **Shared Storage via EFS** | EC2, EFS | Scalable NAS |

Each project includes diagrams, step lists, and is mapped to AWS exam objectives.

---

🙌 *Contributions welcome!* If you spot an improvement or want to add a lab, open a pull request. Stay curious, and good luck on your AWS journey!
