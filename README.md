👋 Namdeo Pawar | DevOps & Cloud Enthusiast
AWS Certified Solutions Architect - Associate | AWS Certified DevOps Engineer - Professional | Red Hat Certified System Administrator | Red Hat Certified Specialist in Ansible Automation
📍 Location: India | 🌐 Website: namacloudops.in

🚀 About Me
I’m a DevOps Engineer with over 3 years of experience, passionate about automating infrastructure and optimizing cloud environments. My journey has involved designing and deploying scalable cloud architectures, implementing CI/CD pipelines, and leading migration projects across AWS, GCP, and on-premise environments.

I have hands-on experience managing cloud infrastructure, automating deployments, and integrating security into cloud workflows. I strive to deliver solutions that reduce manual overhead, increase system reliability, and ensure seamless service delivery.

🔧 Tech Stack & Skills
Cloud Platforms: AWS (EC2, S3, RDS, EKS, Lambda), GCP
Infrastructure as Code: Terraform, CloudFormation, Ansible
CI/CD: Jenkins, GitHub Actions, ArgoCD
Containerization & Orchestration: Docker, Kubernetes (EKS)
Scripting: Python, Shell Scripting
Monitoring & Observability: Prometheus, Grafana, AWS CloudWatch
Version Control: Git, GitHub, GitLab
Web Servers: Nginx, Apache Tomcat
Database Management: MySQL, PostgreSQL
Security: AWS IAM, Security Groups, NACLs, SAML Integration
OS Administration: Linux (Ubuntu, RHEL)
💼 Projects & Contributions
1. Three-Tier Web Application on Amazon EKS using Jenkins CI/CD
Tech Stack: ReactJS, NodeJS, MongoDB, AWS EKS, Terraform, Jenkins
GitHub Repository
This project demonstrates deploying a complete three-tier web application on AWS EKS using Jenkins for CI/CD. It covers all the necessary steps for setting up the infrastructure using Terraform and automating the deployment pipeline.

Key Highlights:
ReactJS frontend, NodeJS API server, MongoDB database
Infrastructure managed with Terraform
Continuous Integration/Delivery using Jenkins
Deployed on Amazon EKS with automated scaling and monitoring
2. Linux Account Central Application Setup
Tech Stack: Nginx, Java, PostgreSQL
This project involves a detailed setup of a secure Java-based web application, running on Linux with Nginx and PostgreSQL. It also includes server hardening techniques and security configurations.

Key Highlights:
Customized Nginx reverse proxy configuration
PostgreSQL integration with Java application
Security headers and optimized access management
3. Google SSO with Nginx using Okta and Vouch
In this project, I implemented Single Sign-On (SSO) with Google using Okta and Vouch on Nginx. It showcases how to integrate external identity providers with a secure authentication layer for web applications.

🛠️ Setup Guide for the Three-Tier Web Application Project
Here’s how you can set up my Three-Tier Application on AWS EKS project locally or on the cloud:

Clone the Repository:

bash
Copy code
git clone https://github.com/namdeopawar/three-tier-app-deployment-eks.git
cd three-tier-app-deployment-eks
Install Dependencies: Make sure you have installed the following dependencies:

AWS CLI
kubectl
Terraform
Jenkins
Docker (for Jenkins and building images)
Set Up Jenkins:

You can either run Jenkins locally or use Docker to set it up. Use the following command to spin up a Jenkins container:
bash
Copy code
docker run -d -p 8080:8080 -p 50000:50000 --name jenkins jenkins/jenkins:lts
Configure Jenkins Pipeline:

Set up the pipeline defined in the repository’s Jenkinsfile.
Make sure Jenkins has the required plugins for integration with Kubernetes and Terraform.
Provision Infrastructure using Terraform:

Navigate to the infra directory and run Terraform commands:
bash
Copy code
terraform init
terraform apply
This will provision the necessary infrastructure on AWS, including the EKS cluster.
Deploy the Application:

Once the EKS cluster is ready, Jenkins will automate the deployment of the ReactJS frontend, NodeJS backend, and MongoDB database onto Kubernetes.
📫 Connect with Me
LinkedIn: Namdeo Pawar
GitHub: github.com/namdeopawar
Website: namacloudops.in
📄 Certifications
AWS Certified Solutions Architect - Associate
AWS Certified DevOps Engineer - Professional
Red Hat Certified System Administrator (RHCSA)
Red Hat Certified Specialist in Ansible Automation
Feel free to explore my repositories and reach out for collaboration, discussions, or consulting!
