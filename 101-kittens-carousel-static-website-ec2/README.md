# 🐱 Kittens Carousel – Static Website Project on AWS EC2

This project showcases a static website deployment on **Amazon EC2** using **AWS CloudFormation**.  
It features an interactive kitten image carousel and is designed to demonstrate basic DevOps & cloud provisioning skills with Infrastructure as Code (IaC) principles.

---

## 📦 Tech Stack

- **Amazon EC2** (t2.micro – Free Tier)
- **Amazon Linux 2**
- **Apache Web Server**
- **AWS CloudFormation**
- **UserData Bash Scripting**
- **Git & GitHub**

---

## 🚀 Deployment Overview

- EC2 instance launched via CloudFormation
- Apache installed and started automatically using UserData script
- Static website files pulled directly from GitHub repo
- Website becomes publicly available via EC2 Public DNS


---

## 🧠 What I Demonstrated in This Project

- Provisioning infrastructure with AWS CloudFormation
- Installing and configuring Apache on Amazon Linux 2
- Automating deployment with Bash and UserData
- Hosting static web content on EC2
- Pulling resources directly from GitHub

---

## 🛠 Setup & Usage

1. Clone this repo:
   ```bash
   git clone https://github.com/macdevopss/aws-projects.git
   cd 101-kittens-carousel-static-website-ec2
   ```
2. Launch the CloudFormation stack using `kittens-carousel.yaml`
3. After deployment, open your EC2 instance’s public DNS in your browser to view the website.

---

## 👤 Author

**macdevopss**  
🚀 Cloud & DevOps Enthusiast  
🌍 [GitHub Profile](https://github.com/macdevopss)

---

## 📜 License