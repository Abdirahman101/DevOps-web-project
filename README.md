# ☁️ Cloud Web App Deployment & GitHub Integration

This repository showcases two foundational DevOps projects designed to demonstrate how to deploy a Java web application in the cloud using AWS and integrate it with GitHub for version control. Together, these projects simulate a typical modern DevOps workflow used in real-world software delivery pipelines.

---

## 🔧 Project 1: Deploying a Web App in the Cloud

In this project, we provisioned a virtual server (EC2 instance) on AWS to host a Java-based web application. Using Apache Maven and Amazon Corretto (Java 8), we generated and ran a basic Java web app. All development and server configuration were performed using Visual Studio Code via a secure SSH connection.

Key highlights:
- Deployed and configured an EC2 instance with secure SSH access
- Installed and validated build tools (Apache Maven & Amazon Corretto)
- Generated a Java web application using Maven archetypes
- Remotely edited and managed source code through VS Code

> 📘 For step-by-step setup instructions, refer to:  
> `Project 1 - Set Up a Web App in the Cloud.pdf`

---

## 🔗 Project 2: Integrating GitHub for Version Control

Building on the first project, we introduced Git for version control and connected the EC2-hosted project to a GitHub repository. This enabled seamless source code management and remote collaboration capabilities.

Key highlights:
- Installed Git on the EC2 instance and initialized a local repository
- Connected the local Git repository to GitHub
- Committed and pushed changes to track project evolution
- Demonstrated best practices such as author configuration and commit messaging

> 📘 For implementation details, refer to:  
> `Project 2 - Connect a GitHub Repo with AWS.pdf`

---

## 🧰 Technologies Used
- **AWS EC2** – Cloud-based virtual server
- **Visual Studio Code** – IDE with Remote SSH support
- **Apache Maven** – Java project management and build tool
- **Amazon Corretto 8** – Java runtime used in the EC2 environment
- **Git & GitHub** – Source control and remote collaboration

---

## ✅ Outcomes & Learnings

These projects helped reinforce practical skills in:
- Cloud infrastructure setup (IAM, EC2, SSH)
- Remote development workflows
- Java-based web app generation and configuration
- Source control with Git and GitHub
- Following best practices in cloud security and DevOps

---

## 🚀 What's Next

In future phases, this project will explore:
- Dependency management using AWS CodeArtifact
- CI/CD automation using AWS CodePipeline
- Monitoring and logging with AWS CloudWatch

---

> 💡 Whether you're learning DevOps or setting up your own cloud pipeline, these projects offer a strong foundation to build on.
