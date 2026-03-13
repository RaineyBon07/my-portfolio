# Cloud Portfolio Website
Cloud-hosted portfolio deployed on AWS using S3, CloudFront, and CI/CD with GitHub Actions.

![AWS](https://img.shields.io/badge/Platform-AWS-orange)
![S3](https://img.shields.io/badge/Storage-Amazon_S3-green)
![CloudFront](https://img.shields.io/badge/CDN-CloudFront-blue)
![Monitoring](https://img.shields.io/badge/Monitoring-CloudWatch-yellow)
![Alerts](https://img.shields.io/badge/Notifications-SNS-red)
![CI/CD](https://img.shields.io/badge/Automation-GitHub_Actions-purple)

## Live Website

Primary URL (via CloudFront CDN)  
https://d2ch139wvdmm4l.cloudfront.net/

Direct S3 Website Endpoint (origin)  
http://lorraine-portfolio-2026.s3-website.eu-north-1.amazonaws.com

---

# Project Overview

This project is a **cloud-hosted personal portfolio website** designed to showcase my technical skills, cloud engineering projects, and professional background.

The site is built using **HTML and CSS** and deployed on **AWS S3 Static Website Hosting**. Deployment is automated using **GitHub Actions**, enabling continuous delivery from the GitHub repository to the AWS S3 bucket.

This project demonstrates practical experience with:

- Cloud infrastructure deployment
- Version control using Git
- Continuous Integration and Continuous Deployment (CI/CD)
- AWS monitoring and alerting

---

# Architecture

The portfolio follows a cloud deployment architecture using AWS services and CI/CD automation.

GitHub Repository
│
▼
GitHub Actions CI/CD Pipeline
│
▼
Amazon S3 (Static Website Hosting)
│
▼
Amazon CloudFront (Global CDN + caching + HTTPS)
│
▼
Public Portfolio Website

Monitoring and alerting are implemented using:

- AWS CloudWatch for metrics and monitoring
- AWS SNS for alert notifications

---

# Technologies Used

**Frontend**
- HTML
- CSS

**Cloud & Infrastructure**
- AWS S3 (Static Website Hosting)
- AWS CloudFront (Content Delivery Network)
- AWS IAM (Access Management)

**Monitoring & Alerts**
- AWS CloudWatch
- AWS SNS

**Development & CI/CD**
- GitHub (Version Control)
- GitHub Actions (Automated Deployment)
- Visual Studio Code (Development Environment)

---

# Website Sections

The portfolio currently includes the following sections:

## About Me
Overview of my background and interest in cloud engineering and technology.

## Skills
A summary of technical skills, cloud tools, and technologies.

## Projects
A showcase of projects demonstrating cloud and DevOps experience.

## Contact
Information on how to connect professionally.

---

# Current Project

## Cloud Portfolio Website

This repository contains the source code and deployment configuration for my personal portfolio website hosted on AWS.

The goal of this project is to demonstrate real-world experience with:

- Cloud infrastructure
- CI/CD automation
- Static website deployment
- Monitoring and alerting

Future updates will include additional cloud engineering and DevOps projects.

---

# Deployment

The website deployment process is fully automated.

### Deployment Workflow

1. Code is pushed to the GitHub repository
2. GitHub Actions triggers an automated workflow
3. The workflow deploys updated files to the AWS S3 bucket
4. CloudFront distributes the updated content globally
5. Monitoring and alerts are handled via CloudWatch and SNS

---

# Repository Structure

my-portfolio
│
├── index.html
├── style.css
├── assets/
│   ├── images
│   └── icons
│
└── .github
└── workflows
└── deploy.yaml

---

# Future Improvements

Planned enhancements for this project include:

- Adding additional cloud and DevOps projects
- Improving monitoring and alerting configuration
- Enhancing website responsiveness and UI design
- Expanding CI/CD workflows
- Adding infrastructure automation using Infrastructure as Code (IaC)

---

# Author

**Lorraine Bonney**

Cloud and DevOps enthusiast focused on building practical cloud solutions, automation workflows, and scalable infrastructure.
        
