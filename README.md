# Muralidharan M N

**Cloud & DevOps Engineer (entry-level)** · AWS Certified Cloud Practitioner · HashiCorp Certified Terraform Associate · India

I build and automate AWS infrastructure with Terraform and GitHub Actions. When something breaks, I trace it to the root cause and write up what broke, why, and how I fixed it.

**Highlights**
- Built a three-tier AWS environment as **49 Terraform resources** (Multi-AZ RDS, Auto Scaling, no SSH) and cut Checkov findings from **39 to 0**.
- Built a CI/CD pipeline that takes a Flask app from **merge to live in 1m 52s**: tests, Docker build, Trivy scan, deploy over SSM, health check.
- No AWS access keys in any of my pipelines (GitHub OIDC), and no open SSH port on my servers (Systems Manager).

**Open to:** entry-level Cloud Support, Cloud Operations and DevOps roles.

[Portfolio](https://d1gfj90rneo89i.cloudfront.net) · [LinkedIn](https://www.linkedin.com/in/muralidharan-m-n-78a2522b8) · [Email](mailto:muralidharan366636@gmail.com)

---

## Featured Projects

| Project | What it shows | Stack |
| --- | --- | --- |
| **[Three-Tier Infrastructure with Terraform](https://github.com/muralidharan666666-dev/aws-three-tier-terraform)** | 49 resources as code, remote state with locking, full rebuild in ~15 min, no port 22 open | Terraform · VPC · ALB · ASG · RDS Multi-AZ · Secrets Manager · CloudTrail |
| **[Automated CI/CD Pipeline for a Flask App](https://github.com/muralidharan666666-dev/aws-automated-deployment-pipeline)** | Merge to live in 1m 52s: tests, Docker build, Trivy scan, deploy over SSM (no SSH, no AWS keys), health check, and a tested CPU alarm | GitHub Actions · Docker · Trivy · ECR · EC2 · SSM · Terraform · CloudWatch · SNS |
| **[Microservices on ECS Fargate](https://github.com/muralidharan666666-dev/aws-ecs-fargate-microservices)** | Two services that deploy, scale and fail independently, with path-based routing | Docker · ECR · ECS Fargate · ALB · DynamoDB |
| **[Serverless Tasks API](https://github.com/muralidharan666666-dev/aws-serverless-tasks-api)** | Secure CRUD API: WAF in front, and a Cognito token check before any Lambda runs | Lambda · API Gateway · DynamoDB · Cognito · WAF |
| **[Portfolio on S3 + CloudFront with CI/CD](https://github.com/muralidharan666666-dev/aws-s3-cloudfront-static-website)** | Private bucket behind OAC, auto-deploy on every push using GitHub OIDC (no access keys) | GitHub Actions · OIDC · S3 · CloudFront |
| **[Event-Driven Order Processing](https://github.com/muralidharan666666-dev/aws-event-driven-order-system)** | Decoupled async pipeline where no order is lost, thanks to retries and a dead-letter queue | API Gateway · Lambda · SQS · SNS |

The Terraform project is a rebuild of my [manual console version](https://github.com/muralidharan666666-dev/aws-three-tier-web-application), so you can compare the two side by side.
Every repo includes an architecture diagram and real test results, and most include a **"Problems I ran into"** section.

---

## Skills

| Area | Tools |
| --- | --- |
| **Cloud (AWS)** | EC2, VPC, IAM, S3, RDS, Lambda, API Gateway, DynamoDB, ECS Fargate, ECR, CloudFront, SQS, SNS, Cognito, WAF, Secrets Manager, Systems Manager (SSM) |
| **IaC, Containers & CI/CD** | Terraform (modules, remote state, S3 locking), GitHub Actions, OIDC federation, Docker, Trivy, Checkov |
| **Observability** | CloudWatch Logs & Alarms, VPC Flow Logs, CloudTrail |
| **Other** | Linux, Bash, Python, pytest, Git |

---

## Certifications

- **HashiCorp Certified: Terraform Associate (004)**, Sep 2026
- **AWS Certified Cloud Practitioner (CLF-C02)**, Oct 2025
- **AWS re/Start Graduate**, Sep 2025
