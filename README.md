<h1 align="center">Hi, I'm Love Uzowulu 👋</h1>

<h3 align="center">DevOps \& Cloud Infrastructure Engineer · AWS · Terraform · Kubernetes · GitOps</h3>



<p align="center">

&#x20; <a href="mailto:your@email.com">

&#x20;   <img src="https://img.shields.io/badge/Email-your@email.com-D14836?style=for-the-badge\&logo=gmail\&logoColor=white" alt="Email" />

&#x20; </a>

&#x20; \&nbsp;

&#x20; <img src="https://img.shields.io/badge/ALTSchool%20Africa-Cloud%20Engineering%20Diploma%20%7C%202025-0A66C2?style=for-the-badge\&logo=graduation-cap\&logoColor=white" alt="ALTSchool" />

</p>



\---



\## 🧭 Core Mission



ALTSchool Africa-trained Cloud \& DevOps Engineer specialising in production-grade AWS infrastructure, container orchestration, and end-to-end CI/CD automation. I turn complex, distributed systems into reliable, repeatable deployments — using Terraform, Kubernetes, and GitOps principles from the ground up.



\---



\## 🛠️ Featured Ecosystem



\### ☁️ Cloud \& Infrastructure

!\[AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square\&logo=amazonaws\&logoColor=white)

!\[Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square\&logo=terraform\&logoColor=white)

!\[Amazon EKS](https://img.shields.io/badge/Amazon%20EKS-FF9900?style=flat-square\&logo=amazonaws\&logoColor=white)

!\[Amazon RDS](https://img.shields.io/badge/Amazon%20RDS-527FFF?style=flat-square\&logo=amazonrds\&logoColor=white)

!\[AWS Lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?style=flat-square\&logo=awslambda\&logoColor=white)

!\[Amazon S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=flat-square\&logo=amazons3\&logoColor=white)

!\[AWS ACM](https://img.shields.io/badge/AWS%20ACM-DD344C?style=flat-square\&logo=amazonaws\&logoColor=white)

!\[Amazon CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square\&logo=amazonaws\&logoColor=white)



\### 🐳 Orchestration \& Containers

!\[Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square\&logo=kubernetes\&logoColor=white)

!\[Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square\&logo=helm\&logoColor=white)

!\[Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)

!\[AWS Load Balancer Controller](https://img.shields.io/badge/AWS%20LBC-FF9900?style=flat-square\&logo=amazonaws\&logoColor=white)



\### ⚙️ CI/CD \& Automation

!\[GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square\&logo=githubactions\&logoColor=white)

!\[GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square\&logo=gitlab\&logoColor=white)

!\[Terraform Cloud](https://img.shields.io/badge/Terraform%20CI/CD-7B42BC?style=flat-square\&logo=terraform\&logoColor=white)



\### 🗄️ Data \& Messaging

!\[Amazon DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square\&logo=amazondynamodb\&logoColor=white)

!\[MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square\&logo=mysql\&logoColor=white)

!\[PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)

!\[Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square\&logo=redis\&logoColor=white)

!\[RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square\&logo=rabbitmq\&logoColor=white)



\### 🧑‍💻 Languages \& Scripting

!\[HCL](https://img.shields.io/badge/HCL-7B42BC?style=flat-square\&logo=terraform\&logoColor=white)

!\[Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)

!\[Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square\&logo=gnubash\&logoColor=white)

!\[YAML](https://img.shields.io/badge/YAML-000000?style=flat-square\&logo=yaml\&logoColor=white)



\---



\## 🏗️ Engineering Proof — Core Repositories



\### 🪨 \[`project-bedrock-capstone`](https://github.com/LoveAlways1/project-bedrock-capstone) — ALTSchool Capstone Project



> \*\*Production-style AWS EKS deployment for a microservices retail application, fully automated with Terraform and GitHub Actions CI/CD.\*\*



| Attribute | Detail |

|---|---|

| \*\*Stack\*\* | Terraform · AWS EKS · Helm · GitHub Actions · Lambda · CloudWatch · RDS (MySQL + PostgreSQL) · DynamoDB · Redis · RabbitMQ |

| \*\*Problem Solved\*\* | Provisioning a fully automated, production-grade Kubernetes environment with managed databases, event-driven serverless extensions, TLS termination, and observability — all as code |

| \*\*Live URL\*\* | `https://store.chnd.space` (HTTPS with ACM + ALB, HTTP→HTTPS redirect) |

| \*\*Architecture Highlights\*\* | Multi-AZ VPC with public/private subnets · EKS managed node group · AWS Load Balancer Controller for ALB Ingress · Helm-based application deployment with per-service data backend overrides |

| \*\*Serverless Extension\*\* | S3 event notification triggers a Lambda function (`bedrock-asset-processor`) on file upload — logs processed filename to CloudWatch |

| \*\*Security Design\*\* | Least-privilege IAM (separate dev-view and cicd-deploy users) · RDS in private subnets · S3 bucket with public access blocked · No hardcoded credentials in workflow files |

| \*\*Observability\*\* | EKS control plane logging (api, audit, authenticator, controllerManager, scheduler) · CloudWatch Container Insights with 4 log groups |

| \*\*CI/CD Behaviour\*\* | PR to `main` → `terraform plan` · Merge to `main` → `terraform apply` · Manual trigger via `workflow\_dispatch` |



\---



\### 🚀 \[`starttech-infra`](https://github.com/LoveAlways1/starttech-infra) — StartTech Cloud Infrastructure



> \*\*Terraform-driven AWS infrastructure for a startup-scale platform with GitHub Actions automation, monitoring, and shell scripting.\*\*



| Attribute | Detail |

|---|---|

| \*\*Stack\*\* | Terraform (HCL 98.8%) · Shell Scripts · GitHub Actions · AWS · Monitoring configs |

| \*\*Problem Solved\*\* | Codifying repeatable, version-controlled cloud infrastructure for a startup environment — with integrated monitoring and automated deployment scripts |

| \*\*Architecture Highlights\*\* | Terraform-managed AWS resources · Monitoring directory for observability configs · Automation scripts for operational tasks |

| \*\*CI/CD\*\* | GitHub Actions workflows for automated infrastructure delivery |

| \*\*Note\*\* | CloudFront distribution planned but blocked by AWS account verification during deployment — documented transparently |



\---



\### 📋 \[`month-one-assessment`](https://github.com/LoveAlways1/month-one-assessment) — Terraform IaC Assessment



> \*\*3rd semester Month 1 Terraform assessment — demonstrating foundational infrastructure-as-code competence on AWS.\*\*



| Attribute | Detail |

|---|---|

| \*\*Stack\*\* | Terraform (HCL) · AWS |

| \*\*Problem Solved\*\* | Declarative provisioning of AWS resources using modular Terraform — demonstrating IaC fundamentals |



\---



\## 🎓 Education



| Programme | Institution | Year |

|---|---|---|

| Diploma in Cloud Engineering | ALTSchool Africa | 2025 |



\---



\## 🎯 Current Focus



```

▸ Deepening Kubernetes expertise — RBAC, namespace isolation, multi-tenant cluster patterns

▸ Advancing Terraform module design for multi-region AWS deployments

▸ Exploring ArgoCD GitOps workflows for zero-downtime, declarative delivery

▸ Building toward AWS certifications (Solutions Architect / DevOps Engineer)

```



\---



\## 📊 GitHub Activity



<p align="center">

&#x20; <img height="160em" src="https://github-readme-stats.vercel.app/api?username=LoveAlways1\&show\_icons=true\&theme=github\_dark\&hide\_border=true\&count\_private=true\&include\_all\_commits=true" />

&#x20; <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=LoveAlways1\&layout=compact\&theme=github\_dark\&hide\_border=true\&langs\_count=6" />

</p>



\---



<p align="center">

&#x20; <i>"Infrastructure is code. Code is craft. Ship it right."</i>

</p>

