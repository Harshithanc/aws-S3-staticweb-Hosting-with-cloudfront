# 🚀 Static Website Hosting using AWS S3 & CloudFront

This project demonstrates how I deployed a static website using **Amazon S3** and delivered it globally using **Amazon CloudFront**.

Through this hands-on project, I learned about static website hosting, S3 bucket permissions, CDN, edge locations, and content delivery.

## 📜 Steps I Performed

### 1. Create an S3 Bucket

* Created an S3 bucket for hosting the static website.
* Configured the required public access settings.

### 2. Configure Static Website Hosting

* Enabled **Static Website Hosting**.
* Set `index.html` as the entry point.

### 3. Upload Website Files

Uploaded:

* HTML files
* CSS files
* JavaScript files
* Images

### 4. Configure Bucket Policy

Added a bucket policy to allow public access to the website objects.

### 5. Test the S3 Website

Accessed the S3 static website endpoint through a web browser.

### 6. Create CloudFront Distribution

* Opened **AWS CloudFront**.
* Created a new distribution.
* Selected the S3 bucket as the origin.
* Configured the distribution settings.
* Selected the required CloudFront price class / edge locations.
* Set `index.html` as the root object.

### 7. Access Website Through CloudFront

After the distribution was deployed, I accessed the website using the **CloudFront distribution domain name**.

## ⚠️ Challenges I Faced

* Images were not loading initially.
* The `images` folder was missing from the S3 bucket.
* Encountered a `404 NoSuchKey` error for `index.html`.
* Had issues with incorrect file paths and folder structure.

## ✅ How I Fixed the Issues

* Uploaded the missing `images` folder.
* Verified the S3 folder and object structure.
* Corrected file paths in the HTML files.
* Verified the bucket policy and public access settings.
* Checked that `index.html` was correctly uploaded.

## 💡 Key Learnings

* Learned how to host a static website using **Amazon S3**.
* Understood how **S3 bucket policies** control access to objects.
* Learned how incorrect object paths can cause `404 NoSuchKey` errors.
* Understood the basic concept of **Content Delivery Networks (CDN)**.
* Learned how **CloudFront edge locations** help deliver content closer to users.
* Gained hands-on experience connecting **S3 with CloudFront**.

## 🌐 Website

**S3 Website:**
[Add your S3 website link here]

**CloudFront Website:**
[Add your CloudFront distribution URL here]

## 🎯 AWS Services Used

* Amazon S3
* Amazon CloudFront

## 🚀 Future Improvements

* Configure HTTPS using CloudFront.
* Use **Origin Access Control (OAC)**.
* Keep the S3 bucket private and allow access through CloudFront.
* Automate deployment using GitHub Actions.

---

☁️ **Learning by building — AWS & DevOps**






## 🛠️ Languages and Tools
## 🛠️ Languages and Tools

[![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)](https://aws.amazon.com/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://www.linux.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)](https://helm.sh/)
[![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)](https://www.terraform.io/)
[![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)](https://www.ansible.com/)
[![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)](https://www.jenkins.io/)
[![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)](https://maven.apache.org/)
[![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/)
[![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)](https://nginx.org/)
[![Oracle SQL](https://img.shields.io/badge/Oracle_SQL-F80000?style=flat-square&logo=oracle&logoColor=white)](https://www.oracle.com/database/)

