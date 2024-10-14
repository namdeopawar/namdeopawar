👋 Hi, I'm Namdeo Pawar | DevOps & Cloud Enthusiast
AWS Certified Solutions Architect - Associate | AWS Certified DevOps Engineer - Professional | Red Hat Certified System Administrator | Red Hat Certified Specialist in Ansible Automation
📍 Location: India | 🌐 Website: namacloudops.in

🚀 About Me
I'm a passionate DevOps Engineer with over 3 years of experience specializing in cloud infrastructure automation and optimization. My expertise lies in:

Designing and deploying scalable cloud architectures.
Implementing CI/CD pipelines for smooth application deployment.
Leading complex cloud migration projects across AWS, GCP, and on-prem environments.
I aim to create reliable systems that minimize manual tasks, improve service uptime, and ensure secure, seamless operations.

🔧 Tech Stack & Skills
Cloud Platforms:

AWS (EC2, S3, RDS, EKS, Lambda), GCP

Infrastructure as Code:

Terraform, CloudFormation, Ansible

CI/CD:

Jenkins, GitHub Actions, ArgoCD

Containerization & Orchestration:

Docker, Kubernetes (EKS)

Scripting:

Python, Shell Scripting

Monitoring & Observability:

Prometheus, Grafana, AWS CloudWatch

Version Control & Web Servers:

Git, GitHub, GitLab, Nginx, Apache Tomcat

Database & OS Administration:

MySQL, PostgreSQL, Linux (Ubuntu, RHEL)

💼 Projects & Contributions
1. Three-Tier Web Application on Amazon EKS using Jenkins CI/CD
Tech Stack: ReactJS, NodeJS, MongoDB, AWS EKS, Terraform, Jenkins

This project demonstrates a fully automated CI/CD pipeline for deploying a three-tier web application on AWS EKS.

Key Highlights:

Frontend in ReactJS, API server in NodeJS, and MongoDB as the database.
Infrastructure management using Terraform.
Automated deployment via Jenkins pipelines on Amazon EKS.
2. Linux Account Central Application Setup
Tech Stack: Nginx, Java, PostgreSQL

A comprehensive setup of a secure Java-based web application, running on Linux with Nginx and PostgreSQL, including server hardening techniques.

Key Highlights:

Nginx reverse proxy configuration.
PostgreSQL integration with Java application.
Enhanced security headers and access controls.
3. Google SSO with Nginx using Okta and Vouch
This project implements Google SSO using Okta and Vouch, adding an extra security layer for web applications.

🛠️ How to Set Up the Three-Tier Web Application Project
1. Clone the Repository
bash
Copy code
git clone https://github.com/namdeopawar/three-tier-app-deployment-eks.git
cd three-tier-app-deployment-eks
2. Install Dependencies
Make sure you have installed the following:

AWS CLI
kubectl
Terraform
Jenkins
Docker
3. Set Up Jenkins
You can either run Jenkins locally or use Docker:

bash
Copy code
docker run -d -p 8080:8080 -p 50000:50000 --name jenkins jenkins/jenkins:lts
4. Configure the Jenkins Pipeline
Set up the pipeline as defined in the Jenkinsfile in the repository.
Install the necessary plugins for Jenkins to interact with Kubernetes and Terraform.
5. Provision Infrastructure using Terraform
Navigate to the infra directory and run the following commands:

bash
Copy code
terraform init
terraform apply
This will provision the required infrastructure on AWS.

6. Deploy the Application
Once the infrastructure is provisioned, Jenkins will handle the automated deployment of the ReactJS frontend, NodeJS backend, and MongoDB database onto Kubernetes.

📫 Connect with Me


🌐 Website: namacloudops.in

📄 Certifications
AWS Certified Solutions Architect - Associate
AWS Certified DevOps Engineer - Professional
Red Hat Certified System Administrator (RHCSA)
Red Hat Certified Specialist in Ansible Automation
Feel free to explore my repositories and reach out for collaboration or discussions!

