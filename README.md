My Portfolio

A personal cloud-hosted portfolio showcasing my work, technical skills, and cloud engineering projects.

This website is deployed on AWS using automated deployment via GitHub Actions, demonstrating practical experience with cloud infrastructure and CI/CD workflows.

Live Website:
http://lorraine-portfolio-2026.s3-website.eu-north-1.amazonaws.com

Project Overview

This project is a static portfolio website built using HTML and CSS and hosted on AWS S3 Static Website Hosting.

The deployment process is automated using GitHub Actions, which pushes updates from the GitHub repository directly to the S3 bucket.

The portfolio highlights:
	•	My technical skills
	•	Cloud and DevOps projects
	•	Professional background
	•	Contact information

The goal of this project is to demonstrate practical experience with cloud deployment, version control, and automated workflows.

Architecture

The portfolio follows a simple cloud deployment architecture:

GitHub Repository
↓
GitHub Actions CI/CD Pipeline
↓
AWS S3 Static Website Hosting
↓
Public Portfolio Website

When changes are pushed to the repository, the GitHub Actions workflow automatically deploys the updated website to the S3 bucket, ensuring the live site always reflects the latest version of the project.

Technologies Used

HTML
CSS
AWS S3 (Static Website Hosting)
AWS IAM (Access Management)
GitHub (Version Control)
GitHub Actions (CI/CD Automation)
Visual Studio Code (Development Environment)

Future Enhancement:
AWS CloudFront (Content Delivery Network)

Website Sections

The portfolio website currently includes the following sections:

About Me
Overview of my background and interests in cloud and technology.

Skills
A summary of technical skills and tools.

Projects
A showcase of projects demonstrating cloud and DevOps experience.

Contact
Ways to connect professionally.

Current Project

Cloud Portfolio Website

This repository contains the infrastructure and source code for my personal portfolio website hosted on AWS.

Future updates will include additional cloud engineering and DevOps projects as they are completed.

Deployment

The site is hosted using AWS S3 Static Website Hosting.

Deployment workflow:
	1.	Code is pushed to the GitHub repository.
	2.	GitHub Actions triggers an automated workflow.
	3.	The workflow deploys the updated files to the AWS S3 bucket.
	4.	The changes are reflected on the live website.

Future Improvements

Planned improvements for this project include:
	•	Adding additional cloud and DevOps projects
	•	Implementing AWS CloudFront for improved performance and global content delivery
	•	Adding HTTPS using AWS services
	•	Enhancing the portfolio design and responsiveness

Author

Lorraine Bonney

Cloud and DevOps enthusiast focused on building practical cloud solutions and automation workflows.

Repository Structure
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
        
